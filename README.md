# floyd_algo


Question to ask yourself...

Q: why does fast and slow guarantee to meet?
A: think about non cycle list, fast is 2x slow, when slow finish, fast can run through the list 2 times already. Now Think about full circular lap, when slow finished one lap, fast already went through two lap and meets right with slow

Q: What is intuitive in the lap run example? 
A: When there is an extension in the running track, slow cannot finish the first before fast and slow meet, this is because of the extension

##The extension caused both fast and slow stop before the finish line during their first lap## 

##Then, fast is able to go on a second lap because it is faster, it first have to cover the small gap to finish the first lap, which is the same distance as the extension!!##

##Now, when slow reach to the end on the first lap, fast will reach to the same point with its second lap!##

[IMG_20210627_231801](https://user-images.githubusercontent.com/67343427/123575237-5160c380-d79f-11eb-8fee-a7e19170cdee.jpg)
