# Advanced-checkpoint-props
Created with CodeSandbox


1. Create a project using create-react-app.
2. Create inside App.js an array of object named products
3. Each object contains a price, and name, and category which can be Electronics and Clothes.
4. Create a component ProductTable, pass products array as props.
5. ProductTable returns a table that has three columns Name, category, and price.
6. Map your array of products inside the table.
7. Use inline props to style your app as you wish.
8. Use proptypes to define your props types


Guide line : 

1. Create thre components  ProductsTable , ProductRow 
2. From App.js we pass props the products array 
3. Inside Products Array we map the products array and return for each element a ProductRow 
4. make sure to pass for Each ProductRow a single product (make sure to give a key for each productRow ) 
5. Define propTypes in productsTable and productRow  (MyComponent.proptypes = ..... ) 
 
 Video aubout props : https://www.youtube.com/watch?v=qA-KepBpGM4&list=PLDdXfoajF9Ntto2VQYHc7Y8LBRhLBIwq5&index=1 
 
 
 
 Proptypes :  https://fr.reactjs.org/docs/typechecking-with-proptypes.html
