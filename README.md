# 🚀 Welcome to `pkg`! 🎉

Introducing `pkg`, the all-in-one command-line tool for managing your projects with flair and style. Just like Rust's Cargo or JavaScript's npm, `pkg` is here to make your life easier with a touch of fun! 😎

## Getting Started 📦

First things first, make sure you have a personal access token. This secret token unlocks the true power of `pkg`! 🛠️

### Installation 💻

Download the pre-compiled `pkg.exe` from the releases page and place it in a directory included in your system's PATH. Now you're ready to roll! 🚀

### Usage 📜

This tool is powered by the magical `pkg` command. Let's dive into what you can do with it.

#### Listing Projects 📝

Want to see all the cool projects in the `NuePkgs` organization? Easy peasy! Just run:

```sh
pkg list --token YOUR_PERSONAL_ACCESS_TOKEN
```
And voilà! You'll get a list of all the repositories. It's like magic! 🧙‍♂️

#### Downloading a Project 📥

Need to download a project for some serious hacking? We've got you covered:

```sh
pkg download [repo] --token YOUR_PERSONAL_ACCESS_TOKEN
```

Replace [repo] with the name of the repository you want to download. We'll zip it up and deliver it right to your doorstep. 🎁

#### Listing Files in a Project 📂

Curious about what's inside a project? Peek inside with:

```sh
pkg list-files [repo] --token YOUR_PERSONAL_ACCESS_TOKEN
```

Replace [repo] with the name of the repository, and you'll get a full list of files and directories. It's like having x-ray vision! 🦸‍♂️

### Example Workflow 🛠️

Here's a quick rundown of how you might use pkg in your daily routine:

```sh
PS K:\pkg-demo> .\pkg.exe list --token ghp_Wf5iKjER1sLpORnLAk1fjWA6SeXyRFUcKbnb           
NuePkgs/.github
NuePkgs/stdlib

PS K:\pkg-demo> .\pkg.exe list-files stdlib --token ghp_Wf5iKjER1sLpORnLAk1fjWA6SeXyRFUcKbnb
LICENSE
README.md
new_plans.md
std
std/cli
std/cli/args_parser
std/cli/args_parser/parser.pkg   
std/cli/args_parser/validator.pkg
std/cli/interactive
std/cli/interactive/menu.pkg     
std/cli/interactive/prompt.pkg   
std/cli/progress
std/cli/progress/bar.pkg
std/cli/progress/spinner.pkg     
std/core
std/core/data_structures
std/core/data_structures/array.pkg
std/core/data_structures/deque.pkg
std/core/data_structures/graph
std/core/data_structures/graph/directed.pkg
std/core/data_structures/graph/undirected.pkg
std/core/data_structures/hash_table.pkg
std/core/data_structures/heap.pkg
std/core/data_structures/list.pkg
std/core/data_structures/queue.pkg
std/core/data_structures/stack.pkg
std/core/data_structures/tree
std/core/data_structures/tree/avl_tree.pkg
std/core/data_structures/tree/binary_tree.pkg
std/core/data_structures/tree/red_black_tree.pkg
std/core/io
std/core/io/console.pkg
std/core/io/file_io.pkg
std/core/io/stream.pkg
std/core/math
std/core/math/advanced.pkg
std/core/math/basic.pkg
std/core/math/calculus.pkg
std/core/math/complex.pkg
std/core/math/linear_algebra.pkg
std/core/math/statistics.pkg
std/core/string
std/core/string/encoding.pkg
std/core/string/formatting.pkg
std/core/string/manipulation.pkg
std/core/system
std/core/system/environment.pkg
std/core/system/memory.pkg
std/core/system/os.pkg
std/core/system/process.pkg
std/crypto
std/crypto/encryption
std/crypto/encryption/aes.pkg
std/crypto/encryption/ecc.pkg
std/crypto/encryption/rsa.pkg
std/crypto/hash
std/crypto/hash/md5.pkg
std/crypto/hash/sha1.pkg
std/crypto/hash/sha256.pkg
std/crypto/hash/sha512.pkg
std/crypto/random
std/crypto/random/csprng.pkg
std/crypto/random/prng.pkg
std/crypto/signing
std/crypto/signing/digital_signature.pkg
std/crypto/signing/hmac.pkg
std/file
std/file/binary
std/file/binary/reader.pkg
std/file/binary/writer.pkg
std/file/csv
std/file/csv/reader.pkg
std/file/csv/writer.pkg
std/file/ini
std/file/ini/reader.pkg
std/file/ini/writer.pkg
std/file/json
std/file/json/generator.pkg
std/file/json/parser.pkg
std/file/xml
std/file/xml/generator.pkg
std/file/xml/parser.pkg
std/file/yaml
std/file/yaml/generator.pkg
std/file/yaml/parser.pkg
std/gui
std/gui/drawing
std/gui/drawing/canvas.pkg
std/gui/drawing/colors.pkg
std/gui/drawing/shapes.pkg
std/gui/events
std/gui/events/event_handler.pkg
std/gui/events/keyboard_events.pkg
std/gui/events/mouse_events.pkg
std/gui/layout
std/gui/layout/box_layout.pkg
std/gui/layout/grid_layout.pkg
std/gui/layout/stack_layout.pkg
std/gui/widgets
std/gui/widgets/button.pkg
std/gui/widgets/checkbox.pkg
std/gui/widgets/label.pkg
std/gui/widgets/radio_button.pkg
std/gui/widgets/text_field.pkg
std/network
std/network/dns
std/network/dns/resolver.pkg
std/network/dns/server.pkg
std/network/email
std/network/email/imap.pkg
std/network/email/pop3.pkg
std/network/email/smtp.pkg
std/network/ftp
std/network/ftp/client.pkg
std/network/ftp/server.pkg
std/network/http
std/network/http/client.pkg
std/network/http/middleware.pkg
std/network/http/server.pkg
std/network/protocols
std/network/protocols/http2.pkg
std/network/protocols/http3.pkg
std/network/protocols/quic.pkg
std/network/socket
std/network/socket/tcp.pkg
std/network/socket/udp.pkg
std/network/websocket
std/network/websocket/client.pkg
std/network/websocket/server.pkg
std/serialization
std/serialization/json
std/serialization/json/deserializer.pkg
std/serialization/json/serializer.pkg
std/serialization/xml
std/serialization/xml/deserializer.pkg
std/serialization/xml/serializer.pkg
std/serialization/yaml
std/serialization/yaml/deserializer.pkg
std/serialization/yaml/serializer.pkg
std/testing
std/testing/benchmark
std/testing/benchmark/memory_benchmark.pkg
std/testing/benchmark/time_benchmark.pkg
std/testing/fuzzing
std/testing/fuzzing/fuzz_tester.pkg
std/testing/mock
std/testing/mock/function_mock.pkg
std/testing/mock/object_mock.pkg
std/testing/unit
std/testing/unit/assert.pkg
std/testing/unit/test_runner.pkg
std/utils
std/utils/caching
std/utils/caching/disk_cache.pkg
std/utils/caching/memory_cache.pkg
std/utils/compression
std/utils/compression/bzip2.pkg
std/utils/compression/gzip.pkg
std/utils/compression/zlib.pkg
std/utils/datetime/formatter.pkg
std/utils/datetime/parser.pkg
std/utils/datetime/timezone.pkg
std/utils/logging
std/utils/logging/console_logger.pkg
std/utils/logging/file_logger.pkg
std/utils/logging/remote_logger.pkg
std/utils/regex
std/utils/regex/matcher.pkg
std/utils/regex/pattern.pkg
std/utils/uuid
std/utils/uuid/v4.pkg
std/utils/uuid/v5.pkg
std/utils/validation
std/utils/validation/input_validator.pkg
std/utils/validation/schema_validator.pkg

PS K:\pkg-demo> .\pkg.exe download stdlib --token ghp_Wf5iKjER1sLpORnLAk1fjWA6SeXyRFUcKbnb
Successfully downloaded and unzipped stdlib
```

### Conclusion 📚

pkg is here to revolutionize the way you manage your projects. It's powerful, easy to use, and just plain fun. So go ahead, give it a spin, and let the magic happen! ✨

Happy coding! 👨‍💻👩‍💻

