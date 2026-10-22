Precompiled Windows `x64-mingw-ucrt` gems support RubyInstaller UCRT Ruby 3.2,
3.3, 3.4, and 4.0. The native extension renders PDFs in-process without a Rust
toolchain or a separate `sghtmltopdf server`. Each bundled Ruby ABI is checked
by installing the gem and rendering PDFs on Windows before publishing.
