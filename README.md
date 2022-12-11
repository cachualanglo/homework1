# homework1

// let arr = [5, 3, 8, 1];
// test 1:

// let filterRange = (arr, a, b) => {
//     for ( let i= 0; i< arr.length ; i++){
//         if( arr[i] >= a && arr[i] <=b ) console.log(arr[i]);
//     }   
// }
// filterRange(arr, 1, 4);

// test 2:
// let filterRangeInPlace = (arr, a, b) =>{
//     for ( let i= 0; i< arr.length ; i++){
//         if( arr[i] <a || arr[i] >b ) arr.splice(i, 1);
//     }
//     console.log(arr);
// }
// filterRangeInPlace(arr,1 , 4);

// test 3:
// let arr = ["HTML", "JavaScript", "CSS"];

// let sorted = (arr) => {
//     let n = arr.length;
//     for ( let i= 0; i< n ; i++){
//         for ( let j= n-1; j> i; j--){
//             if ( arr[j] < arr[j -1]){
//                 const swich = arr[j];
//                 arr[j] = arr[j -1];
//                 arr[j -1] = swich;
//             }
//         }
//     }
//     console.log(arr);
// }
 
// sorted(arr);

// test 4:
// let john = { name: "John", age: 25 };
// let pete = { name: "Pete", age: 30 };
// let mary = { name: "Mary", age: 28 };

// let users = [ john, pete, mary ];

// let names = [];
//  for( let i= 0; i< users.length; i++){
//     names[i] = users[i].name;
//  }

// console.log(names.join(', '));

//test 5:
// let john = { name: "John", surname: "Smith", id: 1 };
// let pete = { name: "Pete", surname: "Hunt", id: 2 };
// let mary = { name: "Mary", surname: "Key", id: 3 };

// let users = [ john, pete, mary ];
// let arrFullName = []
// for ( let i= 0; i< users.length; i++ ){
//     arrFullName[i] = users[i].name +' ' + users[i].surname;
// }


// let usersMapped = [];
// for ( let i= 0; i< users.length; i++ ){
//     usersMapped[i] = {
//         fullName: arrFullName[i],
//         id: users[i].id,
//     }
// }

// console.log(usersMapped);

// test 6:
// let john = { name: "John", age: 25 };
// let pete = { name: "Pete", age: 30 };
// let mary = { name: "Mary", age: 28 };

// let arr = [ pete, john, mary ];
// let n = arr.length;
// let sortByAge = (arr) => {
//     for ( let i= 0; i< n; i++){
//         for ( let j= n-1; j> i; j--){
//             if( arr[j].age < arr[j- 1].age){
//                 let Change = arr[j];
//                 arr[j] = arr[j- 1];
//                 arr[j- 1] = Change;
//             }
//         }
//     }
//     console.log(arr);
// }

// sortByAge(arr);

// test 7:
// test 8:
// let john = { name: "John", age: 25 };
// let pete = { name: "Pete", age: 30 };
// let mary = { name: "Mary", age: 29 };

// let arr = [ john, pete, mary ];
// function getAverageAge(arr) {
//     let sum = 0;
//     for ( let i= 0; i< arr.length; i++){
//         sum+= arr[i].age;
//     }
//     return sum/ 3;
// }

// console.log(getAverageAge(arr));

// test 9:
// let strings = ["Hare", "Krishna", "Hare", "Krishna",
//   "Krishna", "Krishna", "Hare", "Hare", ":-O"
// ];

// for ( let i= 0; i< strings.length; i++){
//     for ( let j= 1; j< strings.length; j++){
//         if (strings[i] == strings[j] ) {
//          strings.splice(j, 1);
//         }
//     }
// }
// console.log(strings);
