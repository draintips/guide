*A meta note about this repository ... and [mdBooks](https://rust-lang-nursery.GitHub.io/mdBook/) as a tool for creating, improving, and **READING** books. mdBook uses Markdown files, making mdBook the best tool to annotate, revise, clarify. In other words* **the best way to really READ important Reference content is to** ***re***-**WRITE IT**.

Here's why:

### Humans learn best by teaching and teach best by learning.

We need to READ ... and that includes using all kinds of technology to ***read*** for us ... but we no longer really need to memorize. **Our future selves will be taught by our current selves.**

Back in the old days of paper textbooks, the best way to READ a textbook was to really USE that book up for your own purposes -- that meant turning it into a REFERENCE for your later self, by adding annotations particularly notes about other related texts, to add color tabs and navigational aids ... in essence, you were re-teaching your future self or maybe someone else who you loaned your REFERENCE text to. **The physical book itself was worth a FRACTION of the value of the time you put into using it -- so, the best strategy was to USE IT UP** and get everything out of that *tool* that you could get.**

The point is worth re-iterating, for its application to mdBook ...*the very best to* ***really*** **READ** *a book, to* ***really understand its content,*** *is to rewrite it in a manner that is more readable TO YOU and/or contains more annotations and links to supporting content you found useful.*  

We can use AI and LLM to do lots of reading for us; we can speedread thousands of arXiv papers and, NOW, with mdBook, we can/should READ some texts much more thoroughly than we did before. For the important References that we need, we continually improve/refactor/update upon any Reference text that we know that we are going to use and rely upon even more in the future.
# MINIMAL viable prototype of mdBook on GH Pages

For your own sanity, **KEEP your initial MVP simple ... as simple as possible, at first.** 

Just get your minimal mdBook lesson working for YOU to learn mdBook. You will quickly be able to complexicate it for your purposes, but ***not if you start with something complex.***

*Do NOT begin by copying or cloning somebody's complexicated cornfuckluation.* **Even this one!!!** 

***Start completely from scratch ... without cloning or copying anything from GitHub.***

- [Install mdBook](https://rust-lang.github.io/mdBook/guide/installation.html) on your local machine, [create your own very first book with MdBook](https://rust-lang.github.io/mdBook/guide/creating.html); you might name it `sandbox`, because that's all it is. Just get mdBook running so that you can play with your `sandbox` installation and book a bit ... *but do not play too much yet,* just KEEP your working `sandbox` book simple. Play comes later.

- Create a brand new, **completely EMPTY** repository on Github, with a very simple name, like `in` as in "initial"

- Clone your new EMPTY `in` repository to your local machine.

- Copy ALL of the files from your first minimal `sandbox` to that new empty `in` initial repository

- In a terminal, cd into your new `in` repository and run the `mdbook serve --open` command to assure yourself that the copied very first local machine-only `sandbox` is now operational, and working as expected in the new `in` repository.

- Commit the working code from `in` repository to GitHub before making any extra additions, configurations, *keep your process as simple as possible* ... and then navigate to your new `in` repository on Github and confirm the commit happened.

- At your `in` repository, go to `Settings`, then `Pages`, under the **Build and Deployment** heading, select the `GitHub Actions`, then configure an **mdBook** Actions to produce a `mdbook.yml` file in the `.github/workflows` directory of your new repository.  **Do NOT add/change anything in the code suggested by GitHub at this point,** *just `Commit changes`, do not change the Commit msg, just `Commit changes`.

- After a few minutes, navigate back to your new repository, go to `Settings`, then `Pages`, click on the link that follows **Your site is live at** and copy that address to the `About` settings on your repositories landing page on Github.

### NOW, create a MINIMALIST backup of `in` 

- Create a backup ... another new completely EMPTY repository on GitHub, with simple, but approriate name, eg `bk` as in backup.

- Clone your `bk` backup repository to your local machine. Then copy ALL of the files of your minimalist initial `in` mdBook repository to this backup `bk` repository, then cd into `bk` directory and run the `mdbook serve --open` command to assure yourself that `bk` minimalist copy of your initial sandbox is working, the use then commit the `bk` repository with the new files back to GitHub.  

- Repeat the GitHub pages drill as you did before for `bk`. Go to `Settings`, then `Pages`, under the **Build and Deployment** heading, select the `GitHub Actions`, then configure an **mdBook** Actions to produce a `mdbook.yml` file in the `.github/workflows` directory of your new repository verify that it works ... you should find that you have to delete the `mdbook.yml` file, which you copied from `in`. 

- Now you have your first `sandbox` on your machine, as well as your initial `in` and backup `bk` ... all idential copies of that first `sandbox` working ... both on your machine and on GitHub ... now, with sufficient backups, you can go ahead and ***complexicate*** your mdBook life at will. 

- NOW you can fork this repository ... or better yet, you should fork some other Reference text in mdBook form from the following table below, which is a forked from [@softprops](https://github.com/softprops) [list of awesome mdbooks](https://github.com/softprops/awesome-mdbook) and experiment with different versions of those mdBooks by copying files from `src` directory and swapping, editing, refactoring ... in other words, *the best way to* ***really*** **READ** *a book, to* ***really understand its content,*** *is to rewrite it in a manner that is more readable TO YOU and/or contains more annotations and links to supporting content you found useful.* 

# Build/Annotate/Improve Upon Your Own mdBook Bookshelf

In order to ***really*** **READ** Reference text that you will rely upon, fork them and then improve them for your own purposes, it's not really so much about removing errors or out-of-date material, ie these References tend to be pretty tight.  It's also not really about your own personal clarifications/simplifications, although it's fine if your want to do that for YOUR copy. It's probably more about adding annotations and notes to related content that you found while diving in to the Reference ... but mostly, your efforts to revise/refactor a Reference text are about ***really*** diving in for your own purposes and **READING** that Reference text in a more thorough manner. 

| Name | Description | Contribute |
|:----|:-----------|:-------:|
| [Async Book](https://rust-lang.GitHub.io/async-book/index.html) | Asynchronous Programming in Rust | [GitHub](https://GitHub.com/rust-lang/async-book) |
| [Async Std Book](https://book.async.rs/) | Async programming in Rust with async-std | [GitHub](https://github.com/async-rs/async-std/tree/master/docs) |
| [Amethyst](https://www.amethyst.rs/book/latest/) | The Amethyst game engine book | [GitHub](https://GitHub.com/amethyst/amethyst) |
| [cargo](https://doc.rust-lang.org/cargo/) | The cargo book | [GitHub](https://GitHub.com/rust-lang/cargo/tree/master/src/doc/src) |
| [Command Line Applications in Rust](https://rust-lang-nursery.GitHub.io/cli-wg/) | A book about writing CLI's in Rust | [GitHub](https://GitHub.com/rust-lang-nursery/cli-wg/tree/master/src) |
| [Discovery](https://docs.rust-embedded.org/discovery/index.html) | The Discovery Book will teach you about microcontrollers, peripherals, sensors and bare metal programming in Rust | [GitHub](https://GitHub.com/rust-embedded/discovery) |
| [The Embedded Rust Book](https://docs.rust-embedded.org/book/index.html) | The Embedded Rust Book will get you up to speed with embedded Rust development | [GitHub](https://GitHub.com/rust-embedded/book) |
| [The Embedonomicon](https://docs.rust-embedded.org/embedonomicon/index.html) | For those that want to dive into the implementation of the foundational crates of the embedded ecosystem | [GitHub](https://GitHub.com/rust-embedded/embedonomicon) |
| [Firefox Data Documentation](https://github.com/mozilla/firefox-data-docs) | A guide for interpreting data gathered by the Firefox Telemetry system | [GitHub](https://github.com/mozilla/firefox-data-docs) |
| [Hello wasm-pack!](https://rustwasm.GitHub.io/wasm-pack/book/) | The wasm-pack guide | [GitHub](https://GitHub.com/rustwasm/wasm-pack/tree/master/docs/src) |
| [mdbook](https://rust-lang-nursery.GitHub.io/mdBook/)| The mdBook user guide | [GitHub](https://GitHub.com/rust-lang-nursery/mdBook)|
| [Pest Book](https://pest.rs/book/) | A thoughtful introduction to the pest parser | [GitHub](https://github.com/pest-parser/book) |
| [Proptest Book](https://altsysrq.github.io/proptest-book/intro.html) | Proptest | [GitHub](https://github.com/AltSysrq/proptest/tree/master/book) |
| [Rust Book with quizzes](https://rust-book.cs.brown.edu/) | A version of the Rust Book with additional quizzes to better understand Rust from the Cognitive Engineering Lab at Brown University in Providence | [GitHub](https://github.com/cognitive-engineering-lab/rust-book) |
| [Rustdoc Book](https://doc.rust-lang.org/stable/rustdoc/) | Guide for Rustdoc | [GitHub](https://github.com/rust-lang/rust/tree/master/src/doc/rustdoc) |
| [Rust and Web Assembly](https://rustwasm.GitHub.io/book/) | How to use Rust and WebAssembly together | [GitHub](https://GitHub.com/rustwasm/book/) |
| [Rust Cookbook](https://rust-lang-nursery.GitHub.io/rust-cookbook/) | Recipes using curated crates | [GitHub](https://GitHub.com/rust-lang-nursery/rust-cookbook)
| [Rust Fuzz Book](https://rust-fuzz.github.io/book/) | Guides and tutorials on how to fuzz Rust code | [GitHub](https://GitHub.com/rust-fuzz/book) |
| [Rust Programming Language](https://doc.rust-lang.org/book/2018-edition/foreword.html) | The book of Rust | [GitHub](https://GitHub.com/rust-lang/book) |
| [Rusty ECMA Book](https://rusty-ecma.github.io/rusty-ecma-book/) | Build JavaScript Development Tools with Rust | [GitHub](https://GitHub.com/freemasen/rusty-ecma-book/) |
