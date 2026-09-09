# Pranav Torti

Favorite Actor

My favorite actor is Shah Rukh Khan.

I like Shah Rukh Khan because he is a very talented actor and has acted in many successful movies. He is known for his hard work and excellent acting skills. His movies are entertaining and inspiring, which is why he is my favorite actor.

---

## Favorite Films

1. The Dark Knight
2. Inception
3. The Prestige

### Songs I Like

- Bohemian Rhapsody
- Hotel California
- Stairway to Heaven

Check out [my favorite city](./MyCity.md) to learn more.s

---

## Cities I Want to Visit

Here are four cities I'd love to visit next, along with why I picked them, and roughly how far and how much it would cost to travel there from Mumbai, my favorite city.

| City       | Reason                        | Distance from Mumbai | Cost      |
|------------|--------------------------------|------------------------|-----------|
| Tokyo      | Amazing food and culture       | 4,200 miles            | $700      |
| Paris      | History and architecture       | 4,350 miles            | $650      |
| Cape Town  | Wildlife and scenic landscapes | 4,800 miles            | $800      |
| New York   | Iconic skyline and energy      | 7,800 miles            | $900      |


---

## Favorite Sayings

> "Talk is cheap. Show me the code."
> — Linus Torvalds

> "Any fool can write code that a computer can understand. Good programmers write code that humans can understand."
> — Martin Fowler

---

## Code Snippet

This snippet is a Java program that writes 100 random integers to a file, one per line, using a `PrintStream` and demonstrating basic exception handling with `try`/`catch`.

```java
//sample code to write 100 random ints to a file, 1 per line

import java.io.PrintStream;
import java.io.IOException;
import java.io.File;

import java.util.Random;

public class WriteToFile
{	public static void main(String[] args)
	{	try
		{	PrintStream writer = new PrintStream( new File("randInts.txt"));
			Random r = new Random();
			final int LIMIT = 100;

```

Source: [WriteToFile.java](https://www.cs.utexas.edu/~scottm/cs307/javacode/codeSamples/WriteToFile.java)