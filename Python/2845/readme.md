# Party at the North Pole

---

Giovana was very happy to be able to send her letter to Santa and receive great gifts. The joy was so great that she resolved to invite all the leprechauns of the good old man to his birthday party that is shortly after Christmas in January. However, she does not want the Grinch to show up at her party to ruin everything so she made a plan.

To hide from the evil Grinch where the party will be, she decided to use the leprechauns' meeting system that works like this: Each leprechauns has a unique numeric identifier and when there is going to be a meeting the house of one of the leprechauns is chosen to host the meeting, but Instead of writing the number of the host leprechaun on the mural of Santa's factory, where everyone can see, it is written the identifier of exactly all the leprechauns with numbers smaller than his and that are coprime to his. This method is also a way of saying that these mural leprechauns must bring food and drinks to the meeting.

Since the Grinch is so bad with numbers to the point of not knowing that two numbers are only called coprimes if the GCD (greatest common divisor) between them is 1, Giovana simply sends a letter to the north pole with the numbers of the leprechauns that must take the food and with that the leprechauns can already figure out where the birthday party will be but the Grinch do not.

Given the letter that the leprechauns received, determine in the house of which leprechaun will be Giovana's birthday party.

## Input

The first line of the entry contains an integer **N** (1 ≤ **N** ≤ 104) which represents the number of numbers written in Giovana's letter. The second line of the entry has **N** integers **Ai** (1 ≤ **Ai** ≤ 105) representing the identifiers of the leprechauns written in the letter.

## Output

The output consists of a single line containing the number of the leprechaun that will host the party of Giovana in his house.

| Input Sample   | Output Sample |
| -------------- | ------------- |
| 4 <br/>7 1 9 3 | 10            |

| 6 <br/>4 6 1 5 3 2 | 7   |
| ------------------ | --- |

| 12 <br/>23 19 15 9 27 3 11 17 5 1 13 25 | 28  |
| --------------------------------------- | --- |

[beecrowd](https://www.beecrowd.com.br/judge/en/problems/view/2845)
