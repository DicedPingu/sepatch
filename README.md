# sepatch

sepatch is a high-level wrapper library around libsepol for manipulating binary SELinux policies. It is intended for use on Android, but also works on GNU/Linux.

**NOTE**: This is not a general purpose library. It only contains functionality relevant to my other projects.

Successful GitHub Actions runs publish the optimized Linux x86_64 Rust library as a downloadable workflow artifact under the run's **Summary** page. This artifact is a library build, not a flashable Magisk module.

## Contributing

([AI policy](https://github.com/chenxiaolong/chenxiaolong/blob/master/AI_POLICY.md))

Bug fix pull requests are welcome! However, I'm unlikely to accept any other changes unless they're directly relevant to my own projects that use this library.

## License

sepatch is licensed under LGPL-2.1-or-later, the same license as the bundled libsepol library. Please see [`LICENSE`](./LICENSE) for the full license text.
