# intellij-library-annotations

`intellij-library-annotations` provides the [IntelliJ IDEA] Annotations library with a bundled IntelliJ annotations.xml for reuse in multiple [IntelliJ IDEA] projects.


## Usage

Install as a git submodule in the root of your IntelliJ project as follows:-

	mkdir -m 0755 -p library .idea-local
	cd library
	git submodule add https://github.com/raphaelcohn/intellij-library-annotations.git annotations
	git submodule update --init --recursive
	cd -
	cd .idea-local
	ln -s ../library/annotations.xml
	cd -


## Dependencies

This submodule expects [intellij-project-template] to be installed at `.idea` in the root of your IntelliJ project


## Licensing

The license for this project is MIT.


[IntelliJ IDEA]: https://www.jetbrains.com/idea/ "IntelliJ IDEA home page"
[intellij-project-template]: https://github.com/raphaelcohn/intellij-project-template.git: "intellij-project-template home page"
