# Jewels-and-Stones
Javascript Solution .charAt and .indexOf

```
var numJewelsInStones = function(J, S) {

    let count = 0
    
    for (let i = 0; i < S.length; i++) {
        if (J.indexOf(S.charAt(i)) != -1) {
            console.log(S.charAt(i))
            count++
        }
    } return count
};

```
