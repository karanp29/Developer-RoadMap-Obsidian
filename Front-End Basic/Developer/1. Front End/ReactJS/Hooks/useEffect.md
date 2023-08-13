
- hook is called every time component renders if parameter is not passed
- if called when something changes need to pass in parameter

````jsx
useEffect(() => {
	//hook run every time component renders
})
````

````jsx
useEffect(() => {
	//hook run when [whenSomethingChanges] get changed
},[whenSomethingChanges])
````

````jsx
useEffect(() => {
	//hook only runs once on initial load
},[])

````


[[Developer/1. Front End/ReactJS/Hooks/Hooks|Hooks]]