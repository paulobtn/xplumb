# xplumb
Small shell script inspired on plan9's plumbing functionality. It works by getting the primary selection and choosing a program to launch the selected text. It opens files using xdg-open (you should configure your mime types), but also works for URLs, directories and man pages. It has two external dependencies:

- X window system
- [xcwd](https://github.com/schischi/xcwd) to get the directory of the focused window
- [xclip](https://github.com/astrand/xclip) to fetch the content from the primary selection

Since it's a personal script and I don't intend to release it, it's very attached to my local configuration so I'm assuming the openbsd ksh shell and the file browser nnn. Modify it as you want.
