If you want to compile this yourself:
- first set up your build environment per the QMK directions.
- Copy and replace the Mammoth75x folder with the contents in the src/wuque/Mammoth75x folder

Once your environment is set up:
- Start QMK MSYS
- The command to compile (to include VIA support) is:
`qmk compile -kb wuque/mammoth75x -km via`
