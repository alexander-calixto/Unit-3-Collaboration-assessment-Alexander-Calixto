Welcome to **TreeLife**, your guide to learning abouth the beauty, diversity, and importance of trees arround the world.


---


## About Us
At **TreeLife**, we're passionate about forests and green living.


Our mission is to:
- Educate people about different types of trees.
- Promote sustainable foresty.
- Encorage reforestaion projects. 


>"The best time to plant a tree was 20 years ago. The second best time in now."
>
> -*Chinese Proverb*



---


## Featured Trees
### Oak Tree
**Scientific Name**: Quercus robur

Known for its strength and longevity, the oak is a symbol of endurance.



<img src="https://bpb-us-e1.wpmucdn.com/sites.dartmouth.edu/dist/0/2024/files/2020/11/EL-1.png" width="300" length="200">


---

### Pine tree
**Scientific Name**: Pinus

Ever green and aromic, pine trees thrive in colder regions.


<img src="https://www.sciencing.com/sciencing/do-pine-trees-need-survive-6549613/c64512e361624e3d9a21ffc39aed7f5c.jpg" width="300" length="200">


---

## Tree Identification Tool
You can use this simple **Javascript** function to identify a tree by its characteristics:


```javascript
function identify_tree(leaf_shape, region){
    if(leaf_Shape == "neadle" && region == "cold"){
        return "Pine Tree"
    } else if(leaf_shape == "broad" && region == "temperate"){
        return "Oak Tree"
    } else {
        return "Unknown Tree"
    }
}
console.log(identify_tree("needle", "cold"))
```