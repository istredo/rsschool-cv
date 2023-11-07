# Andrey Uvarov

# My Contact Info 
* Located in Moscow, Russia
* Phone: +7 999-679-67-99
* E-mail: uvarov6799@gmail.com
* GitHub: [@istredo](https://github.com/istredo)
* Telegram: [@istredo](https://t.me/istredo)

# Summary
I'm currently lerning JS and making small projects. I want to improve my skills and get the job as developer asap.
My goal is to start a career as FrontEnd developer

# Skills
* HTML/CSS
* JavaScript
* React, Redux 
* TypeScript (basic)
* Adobe Photoshop
* Figma

# Code examples
* [GitHub page](https://github.com/istredo)

```

// @param {number[]} nums
let findMin = function (nums) {
	let [left, right] = [0, nums.length - 1];

   while (left < right) {
   const mid = (left + right) >> 1;
   	const suppose = nums[mid];
   	const [leftNum, rightNum] = [nums[left], nums[right]];

   	const target = leftNum < rightNum;
   	if (target) return leftNum;

		const targetLow = suppose < leftNum;
   	if (targetLow) right = mid;
		
   	const targetHight = leftNum <= suppose;
   	if (targetHight) left = mid + 1;	
   }

   return nums[left];
};
```
      
# Education
##### Higher education
* Moscow State Industrial University
	+ Automotive Faculty
	
##### Online learning:
* Interactive course JavaScript for beginners (Udemy)
* Video course "Web development for beginners" 
* Video course "Basics of programming" from CS50 Harvard
* Studying "JavaScript + React from 0 to result" (UlbiTv)

# Languages: 
* English - Pre-intermediate (A2/B1)
* Russian - Native