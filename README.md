# GBADISASM

This is a simple disassembler for Game Boy Advance games.

## Usage

`gbadisasm rom_file -c config_file`
where `rom_file` is the GBA rom to disassemble, and `config_file` is an optional config file that gives hints to the disassembler.

## Config File

The config file consists of a list of statements, one per line. Lines beginning with `#` are treated as comments. An config file `alttpafs.cfg` for The Legend of Zelda: A Link to the Past and Four Swords (U) is provided as an example.
