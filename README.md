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
--snip--
std/utils/validation
std/utils/validation/input_validator.pkg
std/utils/validation/schema_validator.pkg

PS K:\pkg-demo> .\pkg.exe download stdlib --token ghp_Wf5iKjER1sLpORnLAk1fjWA6SeXyRFUcKbnb
Successfully downloaded and unzipped stdlib
```

### Conclusion 📚

pkg is here to revolutionize the way you manage your projects. It's powerful, easy to use, and just plain fun. So go ahead, give it a spin, and let the magic happen! ✨

Happy coding! 👨‍💻👩‍💻

