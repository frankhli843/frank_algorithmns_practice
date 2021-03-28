---
marp: false
---

# Algorithms 
- I believe in taking some time out everyday to sharpen my skills. Part of that is to learn new languages and frameworks while working on projects and the other part is practicing algorithms. 
- If you notice any bugs please submit a ticket!




![img](img/sharpen.jpg)


# Lessons Learned
- Don't name things in a new and unique way. 
    - For example I was making a graph node class that was handling words. I gave node the attribute word instead of value. Halfway through I forgot and kept using value which caused so much grief.
- Don't try to clever and use a hashmap early on when you it to be an array most of the time. It might make things faster but it'll slow you down so much when you forget whether it is an object or a key. Instead use a TODO and just label that it could be a hashmap.
- JS
    - .map will return undefined for anything not returned use .filter(a) to removed that. Note though that this will remove 0
- When in doubt start with brute force and then optimize by logically restricting.
- If you are taking a pointers approach than set up the number of points required for a given calculation.