function greetNames(names) {
  for (let i = 0; i < names.length; i++) {
    const name = names[i]      
    // التحقق مما إذا كان الحرف الأول هو 'j' أو 'J'
    if (name.charAt(0).toLowerCase() === 'j') {
      console.log(`Goodbye J${name.slice(1)}`);
    } else {
      console.log(`Hello ${name}`);
    }
  }
}

// مثال على استخدام الدالة
const namesArray = ["John", "Alice", "james", "Bob", "jill"];
greetNames(namesArray);
