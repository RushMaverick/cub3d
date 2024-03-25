
# Cub3d

In this project, I developed a program that renders text based maps out into a 3D-esque rendition. The project is from the 42 Curriculum, and was developed in C as well as with the Minilibx graphics library. 

The project required a lot of research on my part as I was not familiar with the topics presented in the subject for the project. 

I learned a lot about how to apply mathematical formulas to render 2D into 3D, which used to be like magic to me. Definitely a demanding project which I am glad to have worked on.

## Deployment

To deploy this project, clone it and run

```bash
  make
```

in the root folder. 

After that, you can run 
```bash
  ./cub3d maps/good/basic.cub
```
in order to launch the program with the default map. 
If you want to try out different maps, you can browse the folders or create your own. The maps have to end with .cub to be recognized as well as be formatted in the same way as the basic.cub text file. 

The format has to be as follows:

```bash
NO ./textures/NO.png
SO ./textures/SO.png
WE ./textures/WE.png
EA ./textures/EA.png

C 45,45,45
F 125,125,125

      1111111111111111111111111
      1000000000110000000000001
      1011000001110000000000001
      10010000000000000000000011
111111111011000001110000000000001
100000000011000001110111111111111
11110111111111011100000010001
11110111111111S11101010010001
11000000110101011100000010001
10000000000000001100000010001
10000000000000001101010010001
1100000111010101111101111000111
11110111 1110101 101111010001
11111111 1111111 111111111111 

```

In order to run this program, you need to have glfw installed which is a dependancy for the MLX library. Be sure to install it before running it. 

Enjoy! 

## Screenshots
<img width="959" alt="Screen Shot 2024-03-25 at 10 43 00 AM" src="https://github.com/RushMaverick/cub3d/assets/43605579/a3812121-648b-4790-82ff-8f9d8cb5d81a">
