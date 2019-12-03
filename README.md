# codeNote
my codeNote

# check 使用
```
const rule = [
  {name: 'name', checkType: 'notnull', errorMsg: '请输入姓名'},
  {name: 'contactPhone', checkType: 'phoneno', errorMsg: '请填写正确的电话'}
]
let checkRes = check(object, rule)
if (checkRes) {} else {
  console.log(check.error);
}
```
