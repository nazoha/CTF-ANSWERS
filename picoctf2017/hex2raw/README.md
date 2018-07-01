16進数を文字列に変換するだけ。

- `echo '59c51289ace9cdd4004afa54d297d310' | xxd -r -p | ./hex2raw`

- `python -c "print('59c51289ace9cdd4004afa54d297d310').decode('hex')" | ./hex2raw`
