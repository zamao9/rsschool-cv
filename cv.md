#Temirlan Uzdenov

####Junior Frontend Developer

---

####Contact Information:

**Phone:** +375 25 774 8053

**E-mail:** [mansory_09@mail.ru](mansory_09@mail.ru)

**Telegram:** @zamabars

---

####About me:

Front end developer, looking for a job in organization where can be useful in performing various of tasks related to the direction.

I perform my work qualitatively and responsibly, craving for learning and self - improvement.

Constantly refresh my knowledge to keep up with the latest updates and features in front end development. Try to do my best to upgrade my hard and soft skills in order to develop as IT specialist.

---

####Education:

Mogilev state polytechnical college ( 2011 - 2015 )

**Department** - Marketing

**Speciality** - Marketing Economist

Belarusian Russian University ( 2015 - 2020 )

**Department** - Economy

**Speciality** -
Finance and Credit.

---

####Skills:

- HTML

- CSS,SASS,LESS,SCSS

- JAVASCRIPT

- GIT - FIGMA, ADOBE PHOTOSHOP

---

####Code example:

You probably know the "like" system from Facebook and other pages. People can "like" blog posts, pictures or other items. We want to create the text that should be displayed
next to such an item.

Implement the function which takes an array containing the
names of people that like an item. It must return the display text as shown in
the examples:

```
[]                                -->  "no one likes this"
["Peter"]                         -->  "Peter likes this"
["Jacob", "Alex"]                 -->  "Jacob and Alex like this"
["Max", "John", "Mark"]           -->  "Max, John and Mark like this"
["Alex", "Jacob", "Mark", "Max"]  -->  "Alex, Jacob and 2 others like this"
```

Note: For 4 or more names, the number in `"and 2 others"` simply increases.

**Solution:**

```
let i = 2;
const a = [];
const b = ['Peter'];
const c = ['Jacob', 'Alex'];
const d = ['Max', 'John', 'Mark'];
const e = ['Alex', 'Jacob', 'Mark', 'Max', 'Max', 'Max', 'Max'];

function likes(names) {
  if (names.length === 0) {
    return "no one likes this";
  };
  if (names.length === 1) {
    return `${names[0]} likes this`;
  };
  if (names.length === 2) {
    return `${names[0]} and ${names[1]} like this`;
  };
  if (names.length === 3) {
    return `${names[0]}, ${names[1]} and ${names[2]} like this`;
  };
  if (names.length > 3) {
    return `${names[0]}, ${names[1]} and ${i + (names.length - 4)} others like this`;
  };
};

console.log(likes(a));
console.log(likes(b));
console.log(likes(c));
console.log(likes(d));
console.log(likes(e));

```

---

####My works:

https://zamao9.github.io/restaurant-template/

https://zamao9.github.io/startup-template/

https://zamao9.github.io/noname-template/

---

####Languages:

- RUSSIA - native

- ENGLISH - B1
