# matrix
 Enter the matrix. Simple bash script to fill up a terminal window.

Usage: matrix [options]

Options:
  -d, --density PERCENT    Rain coverage from 0 to 100 (default: 100)
  -s, --speed MULTIPLIER   Speed up the default rain by 1 to 5 (default: 1)
  -c, --color COLOR        green, cyan, blue, magenta, red, yellow, or white
                           (default: green)
      --chars STRING       Characters used for the rain (printable ASCII)
                           (default: 0-9, A-Z, a-z, and @#$%&*+-=)
  -k, --katakana           Use half-width katakana and digits
  -h, --help               Show this help

Keys:
  q          quit
  p, space   pause / resume
  + / -      faster / slower
  c          cycle color

Examples:
  matrix --density 45
  matrix --speed 2 --color cyan
  matrix --katakana



