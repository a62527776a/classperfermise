let array = [
  ['1', '', 'title1', 1, 2, 3],
  ['2', '', 'title2', 4, 5, 6],
  ['11', '1', 'title3', 7, 8, 9],
  ['21', '2', 'title4', 10, 11, 12],
  ['22', '2', 'title5', 13, 14, 15],
  ['111', '11', 'title6', 16, 17, 18],
  ['211', '21', 'title7', 19, 20, 21],
  ['2111', '211', 'title8', 22, 23, 24],
  ['3', '', 'title8', 22, 23, 24],
  ['31', '3', 'title8', 22, 23, 24],
  ['311', '31', 'title8', 22, 23, 24],
  ['3111', '311', 'title8', 22, 23, 24],
  ['31111', '3111', 'title8', 22, 23, 24],
  ['311111', '31111', 'title8', 22, 23, 24],
  ['3111111', '311111', 'title8', 22, 23, 24],
  ['31111111', '3111111', 'title8', 22, 23, 24],
  ['311111111', '31111111', 'title8', 22, 23, 24],
  ['3111111111', '311111111', 'title8', 22, 23, 24],
  ['31111111111', '3111111111', 'title8', 22, 23, 24],
  ['311111111111', '31111111111', 'title8', 22, 23, 24],
  ['3111111111111', '311111111111', 'title8', 22, 23, 24],
  ['31111111111111', '3111111111111', 'title8', 22, 23, 24],
  ['311111111111111', '31111111111111', 'title8', 22, 23, 24],
  ['3111111111111111', '311111111111111', 'title8', 22, 23, 24],
  ['31111111111111111', '3111111111111111', 'title8', 22, 23, 24],
  ['311111111111111111', '31111111111111111', 'title8', 22, 23, 24],
  ['3111111111111111111', '311111111111111111', 'title8', 22, 23, 24],
  ['31111111111111111111', '3111111111111111111', 'title8', 22, 23, 24],
  ['311111111111111111111', '31111111111111111111', 'title8', 22, 23, 24],
  ['4', '', 'title8', 22, 23, 24],
  ['41', '4', 'title8', 22, 23, 24],
  ['411', '41', 'title8', 22, 23, 24],
  ['4111', '411', 'title8', 22, 23, 24],
  ['41111', '4111', 'title8', 22, 23, 24],
  ['411111', '41111', 'title8', 22, 23, 24],
  ['4111111', '411111', 'title8', 22, 23, 24],
  ['41111111', '4111111', 'title8', 22, 23, 24],
  ['411111111', '41111111', 'title8', 22, 23, 24],
  ['4111111111', '411111111', 'title8', 22, 23, 24],
  ['41111111111', '4111111111', 'title8', 22, 23, 24],
  ['411111111111', '41111111111', 'title8', 22, 23, 24],
  ['4111111111111', '411111111111', 'title8', 22, 23, 24],
  ['41111111111111', '4111111111111', 'title8', 22, 23, 24],
  ['411111111111111', '41111111111111', 'title8', 22, 23, 24],
  ['4111111111111111', '411111111111111', 'title8', 22, 23, 24],
  ['41111111111111111', '4111111111111111', 'title8', 22, 23, 24],
  ['411111111111111111', '41111111111111111', 'title8', 22, 23, 24],
  ['4111111111111111111', '411111111111111111', 'title8', 22, 23, 24],
  ['41111111111111111111', '4111111111111111111', 'title8', 22, 23, 24],
  ['411111111111111111111', '41111111111111111111', 'title8', 22, 23, 24],
  ['5', '', 'title8', 22, 23, 24],
  ['51', '5', 'title8', 22, 23, 24],
  ['511', '51', 'title8', 22, 23, 24],
  ['5111', '511', 'title8', 22, 23, 24],
  ['51111', '5111', 'title8', 22, 23, 24],
  ['511111', '51111', 'title8', 22, 23, 24],
  ['5111111', '511111', 'title8', 22, 23, 24],
  ['51111111', '5111111', 'title8', 22, 23, 24],
  ['511111111', '51111111', 'title8', 22, 23, 24],
  ['5111111111', '511111111', 'title8', 22, 23, 24],
  ['51111111111', '5111111111', 'title8', 22, 23, 24],
  ['511111111111', '51111111111', 'title8', 22, 23, 24],
  ['5111111111111', '511111111111', 'title8', 22, 23, 24],
  ['51111111111111', '5111111111111', 'title8', 22, 23, 24],
  ['511111111111111', '51111111111111', 'title8', 22, 23, 24],
  ['5111111111111111', '511111111111111', 'title8', 22, 23, 24],
  ['51111111111111111', '5111111111111111', 'title8', 22, 23, 24],
  ['511111111111111111', '51111111111111111', 'title8', 22, 23, 24],
  ['5111111111111111111', '511111111111111111', 'title8', 22, 23, 24],
  ['51111111111111111111', '5111111111111111111', 'title8', 22, 23, 24],
  ['511111111111111111111', '51111111111111111111', 'title8', 22, 23, 24],
  ['6', '', 'title8', 22, 23, 24],
  ['61', '6', 'title8', 22, 23, 24],
  ['611', '61', 'title8', 22, 23, 24],
  ['6111', '611', 'title8', 22, 23, 24],
  ['61111', '6111', 'title8', 22, 23, 24],
  ['611111', '61111', 'title8', 22, 23, 24],
  ['6111111', '611111', 'title8', 22, 23, 24],
  ['61111111', '6111111', 'title8', 22, 23, 24],
  ['611111111', '61111111', 'title8', 22, 23, 24],
  ['6111111111', '611111111', 'title8', 22, 23, 24],
  ['61111111111', '6111111111', 'title8', 22, 23, 24],
  ['611111111111', '61111111111', 'title8', 22, 23, 24],
  ['6111111111111', '611111111111', 'title8', 22, 23, 24],
  ['61111111111111', '6111111111111', 'title8', 22, 23, 24],
  ['611111111111111', '61111111111111', 'title8', 22, 23, 24],
  ['6111111111111111', '611111111111111', 'title8', 22, 23, 24],
  ['61111111111111111', '6111111111111111', 'title8', 22, 23, 24],
  ['611111111111111111', '61111111111111111', 'title8', 22, 23, 24],
  ['6111111111111111111', '611111111111111111', 'title8', 22, 23, 24],
  ['61111111111111111111', '6111111111111111111', 'title8', 22, 23, 24],
  ['611111111111111111111', '61111111111111111111', 'title8', 22, 23, 24],
  ['7', '', 'title8', 22, 23, 24],
  ['71', '7', 'title8', 22, 23, 24],
  ['711', '71', 'title8', 22, 23, 24],
  ['7111', '711', 'title8', 22, 23, 24],
  ['71111', '7111', 'title8', 22, 23, 24],
  ['711111', '71111', 'title8', 22, 23, 24],
  ['7111111', '711111', 'title8', 22, 23, 24],
  ['71111111', '7111111', 'title8', 22, 23, 24],
  ['711111111', '71111111', 'title8', 22, 23, 24],
  ['7111111111', '711111111', 'title8', 22, 23, 24],
  ['71111111111', '7111111111', 'title8', 22, 23, 24],
  ['711111111111', '71111111111', 'title8', 22, 23, 24],
  ['7111111111111', '711111111111', 'title8', 22, 23, 24],
  ['71111111111111', '7111111111111', 'title8', 22, 23, 24],
  ['711111111111111', '71111111111111', 'title8', 22, 23, 24],
  ['7111111111111111', '711111111111111', 'title8', 22, 23, 24],
  ['71111111111111111', '7111111111111111', 'title8', 22, 23, 24],
  ['711111111111111111', '71111111111111111', 'title8', 22, 23, 24],
  ['7111111111111111111', '711111111111111111', 'title8', 22, 23, 24],
  ['71111111111111111111', '7111111111111111111', 'title8', 22, 23, 24],
  ['711111111111111111111', '71111111111111111111', 'title8', 22, 23, 24],
  ['8', '', 'title8', 22, 23, 24],
  ['81', '8', 'title8', 22, 23, 24],
  ['811', '81', 'title8', 22, 23, 24],
  ['8111', '811', 'title8', 22, 23, 24],
  ['81111', '8111', 'title8', 22, 23, 24],
  ['811111', '81111', 'title8', 22, 23, 24],
  ['8111111', '811111', 'title8', 22, 23, 24],
  ['81111111', '8111111', 'title8', 22, 23, 24],
  ['811111111', '81111111', 'title8', 22, 23, 24],
  ['8111111111', '811111111', 'title8', 22, 23, 24],
  ['81111111111', '8111111111', 'title8', 22, 23, 24],
  ['811111111111', '81111111111', 'title8', 22, 23, 24],
  ['8111111111111', '811111111111', 'title8', 22, 23, 24],
  ['81111111111111', '8111111111111', 'title8', 22, 23, 24],
  ['811111111111111', '81111111111111', 'title8', 22, 23, 24],
  ['8111111111111111', '811111111111111', 'title8', 22, 23, 24],
  ['81111111111111111', '8111111111111111', 'title8', 22, 23, 24],
  ['811111111111111111', '81111111111111111', 'title8', 22, 23, 24],
  ['8111111111111111111', '811111111111111111', 'title8', 22, 23, 24],
  ['81111111111111111111', '8111111111111111111', 'title8', 22, 23, 24],
  ['811111111111111111111', '81111111111111111111', 'title8', 22, 23, 24],
  ['9', '', 'title8', 22, 23, 24],
  ['91', '9', 'title8', 22, 23, 24],
  ['911', '91', 'title8', 22, 23, 24],
  ['9111', '911', 'title8', 22, 23, 24],
  ['91111', '9111', 'title8', 22, 23, 24],
  ['911111', '91111', 'title8', 22, 23, 24],
  ['9111111', '911111', 'title8', 22, 23, 24],
  ['91111111', '9111111', 'title8', 22, 23, 24],
  ['911111111', '91111111', 'title8', 22, 23, 24],
  ['9111111111', '911111111', 'title8', 22, 23, 24],
  ['91111111111', '9111111111', 'title8', 22, 23, 24],
  ['911111111111', '91111111111', 'title8', 22, 23, 24],
  ['9111111111111', '911111111111', 'title8', 22, 23, 24],
  ['91111111111111', '9111111111111', 'title8', 22, 23, 24],
  ['911111111111111', '91111111111111', 'title8', 22, 23, 24],
  ['9111111111111111', '911111111111111', 'title8', 22, 23, 24],
  ['91111111111111111', '9111111111111111', 'title8', 22, 23, 24],
  ['911111111111111111', '91111111111111111', 'title8', 22, 23, 24],
  ['9111111111111111111', '911111111111111111', 'title8', 22, 23, 24],
  ['91111111111111111111', '9111111111111111111', 'title8', 22, 23, 24],
  ['911111111111111111111', '91111111111111111111', 'title8', 22, 23, 24]
]

// // es6 Class
class ParseArrayES6 {
  constructor(inputArray) {
      this.inputArray = inputArray
      this.outputArray = [{
          "sub_data": []
      }]
      this.loopLength = 0
  }
  loop(pId, items) {
      this.inputArray.forEach((item, idx) => {
          this.loopLength++
              if (item[1] === pId) {
                  items.push({
                      main_data: item.slice(2),
                      sub_data: []
                  })
                  delete this.inputArray[idx] // 录入后删掉该条数据 可降低循环次数
                  this.loop(item[0], items[items.length - 1].sub_data)
              }
      })
  }
}

console.time("es6class")
let es6val = new ParseArrayES6(array.slice())
es6val.loop('', es6val.outputArray[0].sub_data)
// console.log(JSON.stringify(val.outputArray))
console.log('es6class', es6val.loopLength) // => 26
console.timeEnd("es6class")     // => loop: 0.2919921875ms

// // ///////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////

loopLength = 0
outputArray = []
array1 = JSON.parse(JSON.stringify(array))

// forEach
let loop = (pId, items) => {
  array1.forEach((item, idx) => {
    loopLength++
    if (item[1] === pId) {
        items.push({
            main_data: item.slice(2),
            sub_data: []
        })
        delete array1[idx] // 录入后删掉该条数据 可降低循环次数
        loop(item[0], items[items.length - 1].sub_data)
    }
  })
}

console.time("forEach")
loop('', outputArray)
// console.log(JSON.stringify(outputArray))
console.log('forEach', loopLength) // => 26
console.timeEnd("forEach")     // => loop: 0.2919921875ms

// ///////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////


// es5 prototype
function ParseArrayEs5 () {
  this.loopLength = 0
  this.outputArray = []
  this.array2 = JSON.parse(JSON.stringify(array))
}

ParseArrayEs5.prototype.loop = function(pId, items) { // 注意 箭头表达式的this指向 与function的this指向不一致 function this指向function 箭头表达式this指向函数的上一级
  this.array2.forEach((item, idx) => {
    this.loopLength++
    if (item[1] === pId) {
        items.push({
            main_data: item.slice(2),
            sub_data: []
        })
        delete this.array2[idx] // 录入后删掉该条数据 可降低循环次数
        this.loop(item[0], items[items.length - 1].sub_data)
    }
  })
}

console.time("es5")

let outputArray666 = new ParseArrayEs5()
outputArray666.loop('', outputArray666.outputArray)
console.log('es5', outputArray666.loopLength) // => 26
console.timeEnd("es5")     // => loop: 0.604248046875ms

// ///////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////

// function convert_table_data_with_level(data, parent_node = "") {
//   var level_1_data = [],
//       new_data = [];
//   for (var i = 0, len = data.length; i < len; i++) {
//       data[i][1] === parent_node ? level_1_data.push(data[i]) : new_data.push(data[i]);
//       recursionLength++;
//   }

//   return level_1_data.map(function(arr) {
//       parent_node = arr[0];
//       return {
//           main_data: arr.splice(2, arr.length - 2),
//           sub_data: convert_table_data_with_level(new_data, parent_node)
//       }
//   });
// }

// console.time("recursion")
// let recursionLength = 0;
// let data_with_level = convert_table_data_with_level(array, '')
// console.log(JSON.stringify(data_with_level) === JSON.stringify(val.outputArray[0].sub_data))
// console.log('recursion', recursionLength) // 42
// console.timeEnd("recursion") // => recursion: 0.098876953125ms


// ///////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////

// babel es6 to es5

// "use strict";

"use strict";

var _createClass = function () { function defineProperties(target, props) { for (var i = 0; i < props.length; i++) { var descriptor = props[i]; descriptor.enumerable = descriptor.enumerable || false; descriptor.configurable = true; if ("value" in descriptor) descriptor.writable = true; Object.defineProperty(target, descriptor.key, descriptor); } } return function (Constructor, protoProps, staticProps) { if (protoProps) defineProperties(Constructor.prototype, protoProps); if (staticProps) defineProperties(Constructor, staticProps); return Constructor; }; }();

function _classCallCheck(instance, Constructor) { if (!(instance instanceof Constructor)) { throw new TypeError("Cannot call a class as a function"); } }

var ParseArrayOri = function () {
    function ParseArray(inputArray) {
        _classCallCheck(this, ParseArray);

        this.inputArray = inputArray;
        this.outputArray = [{
            "sub_data": []
        }];
        this.loopLength = 0;
    }

    _createClass(ParseArray, [{
        key: "loop",
        value: function loop(pId, items) {
            this.inputArray.forEach((item, idx) => {
                this.loopLength++;
                if (item[1] === pId) {
                    items.push({
                        main_data: item.slice(2),
                        sub_data: []
                    });
                    delete this.inputArray[idx]; // 录入后删掉该条数据 可降低循环次数
                    this.loop(item[0], items[items.length - 1].sub_data);
                }
            });
        }
    }]);

    return ParseArray;
}();

console.time("babelClassOri");
var valOri = new ParseArrayOri(array.slice());
valOri.loop('', valOri.outputArray[0].sub_data);
// console.log(JSON.stringify(val.outputArray))
console.log('babelClassOri', valOri.loopLength); // => 26
console.timeEnd("babelClassOri"); // => loop: 0.2919921875ms


"use strict";

var _createClass = function () { function defineProperties(target, props) { for (var i = 0; i < props.length; i++) { var descriptor = props[i]; descriptor.enumerable = descriptor.enumerable || false; descriptor.configurable = true; if ("value" in descriptor) descriptor.writable = true; Object.defineProperty(target, descriptor.key, descriptor); } } return function (Constructor, protoProps, staticProps) { if (protoProps) defineProperties(Constructor.prototype, protoProps); if (staticProps) defineProperties(Constructor, staticProps); return Constructor; }; }();

function _classCallCheck(instance, Constructor) { if (!(instance instanceof Constructor)) { throw new TypeError("Cannot call a class as a function"); } }

var ParseArray = function () {
    function ParseArray(inputArray) {
        _classCallCheck(this, ParseArray);

        this.inputArray = inputArray;
        this.outputArray = [{
            "sub_data": []
        }];
        this.loopLength = 0;
    }

    _createClass(ParseArray, [{
        key: "loop",
        value: function loop(pId, items) {
            var _this = this;

            this.inputArray.forEach(function (item, idx) {
                _this.loopLength++;
                if (item[1] === pId) {
                    items.push({
                        main_data: item.slice(2),
                        sub_data: []
                    });
                    delete _this.inputArray[idx]; // 录入后删掉该条数据 可降低循环次数
                    _this.loop(item[0], items[items.length - 1].sub_data);
                }
            });
        }
    }]);

    return ParseArray;
}();

console.time("Babel6class");
var val = new ParseArray(array.slice());
val.loop('', val.outputArray[0].sub_data);
// console.log(JSON.stringify(val.outputArray))
console.log('Babel6class', val.loopLength); // => 26
console.timeEnd("Babel6class"); // => loop: 0.2919921875ms
