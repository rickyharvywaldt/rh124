# RH124 Notes

This repo contains some (personal) notes as preparation for Red Hat EX200. Red Hat recommends to follow the courses RH124 and RH134, also known as System Administration I, II, respectively. This repo is a work in progress, so feel free to star this repo, or even fork this and create a PR, if you'd like to contribute. 

### Less

I've always been using cat to view the content of a file, but I really prefer to keep my hands as much as possible on my keyboard. The downside of using cat is that you'll need to switch to your mouse to scroll up and down when you have files with many many lines. And here's where less is a better alternative. When you replace cat with less, you can use your arrows keys to "scroll" up and down, but even better; you can use the 'j' and 'k' keys to move down and up. 

### Wc

Word count or wc for short is very useful when you need to count the countable things in a file, like the amount of lines, words, and characters. And that's exactly what it does. 

```
wc /etc/passwd
```

Running the command above will output 3 sets of numbers referring to the amount of lines, words, and characters, in that order. You could also specify to display an individual set of number.

```
wc -l /etc/passwd
```

The -l flag option will only display the amount of lines, and similarly, adding the flag option -w or -c will display the amount of words or characters, respectively. 
