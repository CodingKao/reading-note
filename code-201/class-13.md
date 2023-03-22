# Class 13 Notes

#### Link to article: [Local Storage And How To Use It On Websites](https://www.smashingmagazine.com/2010/10/local-storage-and-how-to-use-it/)


> Local storage is important in web applications because it allows data to be stored on a user's device, making it available even when the user is offline or after a browser restart. It also offers improved performance by reducing the amount of data sent to and from a server, making web applications more responsive. Additionally, local storage increases user privacy, as data is only kept locally on the user's device.

***

## Local Storage And How To Use It On Websites

**Why would a developer use local storage for a web application?**
> Local storage can be used to store data on a user's browser. This allows the application to retain information between page visits and sessions without needing to communicate with a server. This helps to improve the performance of the application and provide a more seamless user experience.

**What information should not be stored in local storage?**
> Local storage should not be used to store sensitive information such as passwords, credit card numbers, or other personal information. This is because local storage is not encrypted and can be easily accessed by anyone with access to the device. Additionally, local storage is not secure and is vulnerable to cross-site scripting (XSS) attacks.

**Local storage can store what type of data? How would you convert it to that type before storing?**
> Local storage can store strings, numbers, Booleans, and objects. To convert a value to the appropriate type before storing, use the String(), Number(), Boolean(), and JSON.stringify() methods respectively. For example, to store an object, you would use JSON.stringify() to convert it to a string before storing it in local storage.
