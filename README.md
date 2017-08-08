# prototype
一个对原型的粗浅理解
* 1.所有的引用类型（数组，对象，函数），__proto__属性值指向它的构造函数的prototype属性值
* 2.所有的引用类型都可以扩展属性
* 3.所有的引用类型都有__proto__ 属性
* 4.当试图得到一个对象的某个属性时，如果这个对象本事没有这个属性，那么会去它的__proto__中寻找（即它的构造函数的prototype中寻找）
