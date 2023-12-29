# Efficient Data Structures for Fast and Low-cost First-order Logic Rule Mining

# 1. Compilation

The source codes for the competitors in the article are included in the following directories:

- SInC: `sinc`
- Opt$_C$: `opt-c`
- Opt$_{CI}$: `opt-ci`
- Opt$_{CIP}$: `opt-cip`
- Opt$_{CIP}^+$: `opt-cipp`

The source codes are written in `C++` and complied by `g++ 8.3.0`. A `CMakeLists.txt` is provided in each directory and can be directly complied.

# 2. Run

The target `sinc` is the executable of our technique. You can refer to all options of the executable by the option `--help`. I.e.,:

```sh
$ ./sinc -help
```

An example command would be:

```sh
$ ./sinc -I /path/to/KB,KBName -O /path/to/output,OutputName
```

The target `test_sinc` includes tests of the project.