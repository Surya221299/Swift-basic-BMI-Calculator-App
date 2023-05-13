# Swift-basic-BMI-Calculator-App
Simple Body Mass Indicator who will calculate using Weight and Height that the user was input using Slider and will return BMI Value and Advise message.

_***App demo BMI Calculator App**_

![Simulator Screen Recording - iPhone 11 - 2023-05-08 at 01 53 36](https://github.com/Surya221299/Swift-basic-BMI-Calculator-App/assets/60531747/1656ab43-2dfc-4014-95fd-5d3069141331)


## **Development Step by Step**
- Create Calculate design Screen using **UISlider** to get the User Weight and Height value and then will be calculated.
- Create second screen named ResultViewController to display user BMI Value and Advice.
- Linking Calculate screen to ResultViewController screen by create **Segue** named goToResult.
- Create new swift file named ResultViewController and inside this file create class who must have same name as file and then connect the **Segue** using **performSegue()** method.
- Adopting **MVC** by creating a CalculatorBrain file and inside this file create **Struct** who have method to set BMI value and advice using **IF/ELSE** conditional statement depending on user BMI Value result.

## **What have I Learned**
- **Learn how to use UISlider.**
- **Learn how to Create Swift Classes.**
- **Understanding the difference between Classes and Structs.**
- **How to create UI Programatically without Storyboards.**
- **Create multi-screen apps by learning Segues and Linking it.**
- **Learn about advanced features of Optionals, including Optional Binding, Optional Chaining and the Nil Coalescing Operator.**
- **Learn to use Color Literals to select colours from a palette.**

>This is a project From Udemy iOS & Swift - The Complete iOS App Development Bootcamp by Dr. Angela Yu, check out the full course at w https://www.udemy.com/course/ios-13-app-development-bootcamp/
