# assignment2-pola

# Venkata Mallikharjuna Rao Pola

###### India Pro Kabaddi League is my favorite sports team

Pro Kabaddi League is my favorite sports team. The Pro Kabaddi League (PKL) is the top flight of the compition in India. **Arjun Deshwal of jaipur is the top raipur of Kabaddi League 2022**. In 24 matches played, he has 237 successful raids and 296 raid points.**The PKL's inaugural season attracted 435 million TV viewers**. The Tournament format is double round-robin league and playoffs. 

---
## India Pro Kabadi league

1. Monu Goyat
2. Siddharth Sirish Desai
3. Rajnish
  - Patna Pirates
  - U Mumba
  - Bengaluru Bulls
  - Bengal Warriors 
  - Dabang Delhi

 Click here to redirect [AboutMe](AboutMe.md)

 ---
 ## Visited Countries
 | Name of the country | Recommanded  Country | days spend there |
 |---------------------|----------------------|------------------|
 | America | America is best country in the world because most of the buatyful places avilable in usa such as parks, museum, NASA etc.. | 12 days |
 | China | To see great wall of china | 15 day |
| London | Recommanded  places in London such as Birmingham, London bridge | 5 days |
| Nephol | Recommanded places in Nephol temples | 10 days | 

----
# Quotes
 > Never put off till tomorrow what you can do the day after tomorrow just as well *MARK TWAIN*

 > Whatever you do, always give 100% unless you're donating blood *BILL MURRAY*

 ----

 # Remove Duplicates from an Array
```
const array = [1, 1, 1, 3, 3, 2, 2];

// Method 1: Using a Set
const unique = [...new Set(array)];

// Method 2: Array.prototype.reduce
const unique = array.reduce((result, element) => {
  return result.includes(element) ? result : [...result, element];
}, []);

// Method 3: Array.prototype.filter
const unique = array.filter((element, index) => {
  return array.indexOf(element) === index;
});
```

[Click here for the source code](https://css-tricks.com/snippets/javascript/remove-duplicates-from-an-array/)







