# practice-Thompson
Lab 2 repo for Web Dev
# Tristen Thompson
## Ginger Root
The sub genre **city-pop** does not have many main stream creators nowadays and I appreciate its ambient qualities, particularly Ginger Root's at the moment. I discovered the band last semester and it has remained in my favorites from then to now. In fact, I am listening to them right now as I write this paragraph. The tracks **"Loretta" and "Jubal District"** from the album *City Slicker* are my top picks from their work. 

***

## List of Musicians
1. Ryan Ike
2. James Shafer
3. Dustan Townsend
4. M. Bulteau
* Dungeon Crawler Carl
* The Infinite Jest
* Jungle of Bones

***

## Lyric Quotes

>
>fare thee well <br>
>It’s been a hell of dream<br>
>Hope you are happy with the ending<br>
>It’s exactly as it seems<br>
>
>~*James Shaffer*

>
>Life is just a bowl of cherries<br>
>Don't take it serious, it's too mysterious<br>
>You work, you save, you worry so<br>
>But you can't take your dough when you go, go, go<br>
>
>So keep repeating it's the berries<br>
>The strongest oak must fall<br>
>The sweet things in life, to you were just loaned<br>
>So how can you lose what you've never owned?<br>
>
>~*Rudy Vallee*

***

## Code Segment

The following code segment allows for the use of different colors in different contexts in dart. The first chunk allows the console messages Good, Waring, and Info to take on the colors green, red, and blue respectively. The other chunks operate similarly, with the second chunk changing the colors of the programs output and the third the color of the returned strings.

```
import 'dart:io';

import 'package:colorize/colorize.dart';

class Messages {
  // Prints
  static void printGood(String message) => print(Colorize(message).green());
  static void printWarning(String message) => print(Colorize(message).red());
  static void printInfo(String message) => print(Colorize(message).blue());

  // Stdouts
  static void outGood(String message) => stdout.write(Colorize(message).green());
  static void outWarning(String message) => stdout.write(Colorize(message).red());
  static void outInfo(String message) => stdout.write(Colorize(message).blue());

  // Returned colored strings
  static String good(String message) => Colorize(message).green().toString();
  static String warning(String message) => Colorize(message).red().toString();
  static String info(String message) => Colorize(message).blue().toString();
}
```

<https://pieces.app/collections/dart>

[MyLocation](https://github.com/Forraclass/practice-Thompson/blob/main/MyLocation.md)