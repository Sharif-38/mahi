// Default by JavaScript

// default value generally use function

function add(num1, num2){
    const result = num1 + num2
    console.log(num1, num2, result)
    return result
}

// const sum = add(34 , 56)  //  34 56 90
const sum = add(23) // 23 undefined NaN
const total = add() // undefined undefined NaN


// Default --- if value is not provided, take this as a default. মানে হলো যখন কোন মান একটা সেট করা হয় তখন এই মানটাকে রান করার জন্য যে পদ্বতি ব্যবহার করা হয় তাকে বলা হয়। 

function run ( num3=0, num4 = 0){  // default value generally set right side. default value we can set 0 or any number(23).
    const result2 = num3 + num4
    console.log(num3, num4, result2)
    return result2
}

const total3 = run(45) // 45 0 45

function fullName ( firs, last=''){
    const full = firs + " " + last
    console.log(full)
    return full
}

const name = fullName('sharif', 'islam') // sharif islam
const name2 = fullName('sharif') // sharif undefined  // we didn't set value for this reason we have gotten undefined value.
const name3 = fullName('sharif') // sharif
