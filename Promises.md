# Promises

- A Promise in JavaScript is an object that represents the eventual completion (or failure) of an asynchronous operation and its resulting value.


> States of a Promise

- Pending → initial state, operation not finished yet.
- Fulfilled → operation completed successfully, returns a value (resolved).
- Rejected → operation failed, returns a reason (error).

> E.g :

 <img width="356" height="241" alt="image" src="https://github.com/user-attachments/assets/e086be99-6b6e-426c-b04b-104f7a7a38e1" />

<br></br>
 
> Types of Promises

- Promise.all() : Runs promises in parallel → returns results ONLY if all succeed.

  <img width="341" height="167" alt="image" src="https://github.com/user-attachments/assets/ba9d7f44-ddb6-4cc5-8766-f7b7f897bee2" />


- Promise.allSettled() : Waits for ALL promises → returns an array of their results
(does NOT stop on error).

  <img width="441" height="420" alt="image" src="https://github.com/user-attachments/assets/22cc4a5a-4843-4270-ac27-62b5e044f459" />


- Promise.any() : Returns the FIRST fulfilled promise.
Ignores rejections (unless ALL reject).

  <img width="320" height="147" alt="image" src="https://github.com/user-attachments/assets/6fd639d0-0ee6-4d05-a81a-df3d845c8484" />

- Promise.race(): Returns the FIRST settled promise (success OR failure).
Fastest wins.

  <img width="493" height="156" alt="image" src="https://github.com/user-attachments/assets/e18d3f93-ab99-48da-9452-619500b31b01" />

