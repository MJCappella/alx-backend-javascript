# ES6 Data Manipulation

This project contains tasks for learning to manipulate data in ECMAScript 2015 (ES6).

## Tasks To Complete

+ [x] 0. **Basic list of objects**<br/>[0-get_list_students.js](0-get_list_students.js) contains a script that exports a function named `getListStudents` with the following requirements:
+ [x] 1. **More mapping**<br/>[1-get_list_student_ids.js](1-get_list_student_ids.js) contains a script that exports a function named `getListStudentIds` with the following requirements:
+ [x] 2. **Filter**<br/>[2-get_students_by_loc.js](2-get_students_by_loc.js) contains a script that exports a function named `getStudentsByLocation` with the following requirements:
+ [x] 3. **Reduce**<br/>[3-get_ids_sum.js](3-get_ids_sum.js) contains a script that exports a function named `getStudentIdsSum` with the following requirements:
+ [x] 4. **Combine**<br/>[4-update_grade_by_city.js](4-update_grade_by_city.js) contains a script that exports a function named `updateStudentGradeByCity` with the following requirements:
  + Returns an array of students for a specific city with their new grade.
  + It should accept a list of students (from `getListStudents`), a `city` (String), and `newGrades` (Array of “grade” objects) as parameters.
  + `newGrades` is an array of objects with this format:
    ```js
    {
      studentId: Number,
      grade: Number,
    }
    ```

+ [x] 5. **Typed Arrays**<br/>[5-typed_arrays.js](5-typed_arrays.js) contains a script that exports a function named `createInt8TypedArray` with the following requirements:
  + Returns a new `ArrayBuffer` with an `Int8` value at a specific position.
  + It should accept three arguments: `length` (Number), `position` (Number), and `value` (Number).
  + If adding the value is not possible the error `Position outside range` should be thrown.

+ [x] 6. **Set data structure**<br/>[6-set.js](6-set.js) contains a script that exports a function named `setFromArray` with the following requirements:
  + Returns a `Set` from an array.
  + It accepts an argument (Array, of any kind of element).

+ [x] 7. **More set data structure**<br/>[7-has_array_values.js](7-has_array_values.js) contains a script that exports a function named `hasValuesFromArray` with the following requirements:
  + Returns a boolean if all the elements in the array exist within the set.
  + It accepts two arguments: a `set` (Set) and an `array` (Array).

+ [x] 8. **Clean set**<br/>[8-clean_set.js](8-clean_set.js) contains a script that exports a function named `cleanSet` with the following requirements:
+ [x] 9. **Map data structure**<br/>[9-groceries_list.js](9-groceries_list.js) contains a script that exports a function named `groceriesList` with the following requirements:
+ [x] 10. **More map data structure**<br/>[10-update_uniq_items.js](10-update_uniq_items.js) contains a script that exports a function named `updateUniqueItems` with the following requirements:
+ [x] 11. **Weak link data structure**<br/>[100-weak.js](100-weak.js) contains a script that meets the following requirements:
 
