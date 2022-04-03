**LOOPS*
## LOOPS
1. <p v-for="str in inputs" :key="str">{{ str}}</p>
2. <p v-for="(str,i) in inputs" :key="i">{{ str }}</p>
THE key class is required in vue by the compiler it can either be the variable assigned values in each iteration or the index of the values in the array these being example 1 and 2 respectivelt.