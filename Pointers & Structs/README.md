## Try the following:

<b>1.</b> Consider the following struct:

```cpp
struct House
{
	bool hasPool;
	int totalRooms;
	short totalPeople;
};
```

<b>a.</b> Create a pointer to <i>House</i> and nullify it
<b>b.</b> Create an instance of <i>House</i> on the heap
<b>c.</b> Add values to the newly created object
<b>d.</b> Destroy the <i>House</i> object

<b>2.</b> Create an array of <i>House</i> objects:

```cpp
House houses[5];
```

<b>a.</b> Loop through each object and assign different values
<b>b.</b> Test and display these values on screen

<b>3.</b> Create an array of <i>House</i> pointers:

```cpp
House* houses[5];
```

<b>a.</b> Loop through the array and instantiate <i>House</i> objects for each pointer
<b>b.</b> Assign data to each element of each <i>House</i> object
<b>c.</b> Create a menu and ask the user which item they wish to remove
<b>d.</b> Find the requested <i>House</i> object and delete it
