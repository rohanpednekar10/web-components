# **Search Bar**

![Demo](images/search-bar.gif)

</br>

## **Using the component**

</br>

### Change *suggestions.js*
</br>

Want different suggestions in the search bar, change `suggestions` list in *suggestions.js* or call api that returns the list.

```javascript
var suggestions = []; // Your list or call api that returns the list.
```
</br>

### Change *search.js*
</br>

Want to trigger different action after search button click, modify `searchButton.onclick` event in *search.js*

```javascript
searchButton.onclick = () => {
	var query = searchBar.value.trim();
	if(query) {
        // Your action or logic.
	}	
}
```

</br>

## **Usage**

</br>

Download the **search-bar** folder and open the *index.html*