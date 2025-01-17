# pgn2gif
Generate gifs from pgn files of your chess games.

## Installation
* You need [python 2.7](https://www.python.org/downloads/) or newer installed.
* Clone the repo with `git clone https://github.com/dn1z/pgn2gif.git`.
* In the cloned directory run
```
pip install -r requirements.txt
```
* If you want to install system wide
```
python setup.py install
```

## Usage
Run pgn2gif with the following options:
```
Usage
    pgn2gif [-h] [-p PATH] [-d DELAY] [-o OUT] [-r]
            [--black-square-color BLACK_SQUARE_COLOR]
            [--white-square-color WHITE_SQUARE_COLOR]

Optional arguments
    -p, --path            Path to the pgn file/folder
    -d, --delay           Delay between moves in seconds
    -o, --out             Name of the output folder
    -r, --reverse         Reverse board
    --black-square-color  Color of black squares in hex
    --white-square-color  Color of white squares in hex
```

__NOTE__

If you choose to run pgn2gif without any other option then:

* pgn file must be present within the current working directory

## Example

### PGN
```
1. Nf3 Nf6 2. d4 e6 3. c4 b6 4. g3 Bb7 5. Bg2 Be7 6. O-O O-O
7. d5 exd5 8. Nh4 c6 9. cxd5 Nxd5 10. Nf5 Nc7 11. e4 d5
12. exd5 Nxd5 13. Nc3 Nxc3 14. Qg4 g6 15. Nh6+ Kg7 16. bxc3
Bc8 17. Qf4 Qd6 18. Qa4 g5 19. Re1 Kxh6 20. h4 f6 21. Be3 Bf5
22. Rad1 Qa3 23. Qc4 b5 24. hxg5+ fxg5 25. Qh4+ Kg6 26. Qh1
Kg7 27. Be4 Bg6 28. Bxg6 hxg6 29. Qh3 Bf6 30. Kg2 Qxa2 31. Rh1
Qg8 32. c4 Re8 33. Bd4 Bxd4 34. Rxd4 Rd8 35. Rxd8 Qxd8 36. Qe6
Nd7 37. Rd1 Nc5 38. Rxd8 Nxe6 39. Rxa8 Kf6 40. cxb5 cxb5
41. Kf3 Nd4+ 42. Ke4 Nc6 43. Rc8 Ne7 44. Rb8 Nf5 45. g4 Nh6
46. f3 Nf7 47. Ra8 Nd6+ 48. Kd5 Nc4 49. Rxa7 Ne3+ 50. Ke4 Nc4
51. Ra6+ Kg7 52. Rc6 Kf7 53. Rc5 Ke6 54. Rxg5 Kf6 55. Rc5 g5
56. Kd4 1-0 
```

### GIF output
<img src="https://thumbs.gfycat.com/HarmfulEveryGreyhounddog-size_restricted.gif">
