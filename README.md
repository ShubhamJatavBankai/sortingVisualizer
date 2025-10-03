# The Sorting Visualizer: A Hands-On Guide to Algorithms 🚀

This interactive web application is your personal sandbox for exploring the world of sorting algorithms. Built with a clean interface using HTML, CSS, and JavaScript, it transforms abstract concepts into dynamic, real-time visuals. You'll see how each algorithm tackles a disordered array, watching the colorful bars move, compare, and swap their way to a perfectly sorted state.

## Key Features ✨
- `Five Foundational Algorithms:` Dive deep into the mechanics of five essential sorting algorithms. You can switch between Bubble Sort, Selection Sort, Insertion Sort, Merge Sort, and Quick Sort with a simple click.

- `Customizable Array:` Not all arrays are created equal! You have complete control to generate a new randomized array of any size from 5 to 100 elements. This allows you to see how different algorithms perform with varying data sizes.

- `Speed Control:` Learning at your own pace is key. Adjust the visualization speed from a slow, methodical crawl to a lightning-fast sprint. This lets you pause and analyze complex steps or get a quick overview of the entire process.

- `Intuitive Interface:` The simple, responsive design makes it easy to navigate. Just select your options from the dropdown menus and hit the Sort button to begin the show.

## Under the Hood: The Code Explained ⚙️
The project's code is carefully organized to be both efficient and easy to understand. Each file has a distinct purpose, working together to create the seamless experience you see.

- `index.html:` The skeleton of the entire application. It contains the main headings, the navigation bar with all the controls (buttons, dropdowns), and the div where the array of bars is dynamically rendered.

- `style.css:` The artistic flair of the project. It handles all the visual aspects, from the button styles and font choices to the key animations that make the bars "dance." It uses different classes like .current, .min, and .done to visually highlight the bars' states during the sort.

- `app.js:` The brain of the operation. This script is in charge of user interaction. It listens for events like a user selecting a new algorithm or clicking the "Generate array" button. It also calls the other scripts to generate the array and start the sorting process.

- `helper.js:` A crucial utility class that handles the core low-level operations. It includes functions to swap the height and values of two bars, compare their values, and pause the execution to control the animation speed. It’s a clean way to abstract the visual complexity from the sorting logic.

- `sort-algorithms.js:` The heart of the project. This is where the magic happens! Each sorting algorithm is implemented as a separate asynchronous function. These functions use the methods from the helper.js class to perform their comparisons and swaps, allowing you to see each step of the sorting process unfold.

## A Look at the Algorithms 🧠
- `Bubble Sort:` This is often the first algorithm people learn. It repeatedly steps through the list, compares adjacent elements, and swaps them if they are in the wrong order. It's a simple but inefficient approach, with a time complexity of <b>O(n<sup>2</sup>).</b>

- `Selection Sort:` This algorithm finds the smallest element in the unsorted portion of the array and swaps it with the first unsorted element. It's more efficient than Bubble Sort in terms of swaps but still has a time complexity of <b>O(n<sup>2</sup>).</b>

- `Insertion Sort:` A great choice for smaller or nearly sorted lists. It builds the final sorted array one item at a time by inserting each element into its correct position within the sorted portion.

- `Merge Sort:` A powerful "divide and conquer" algorithm. It recursively splits the array in half until it can't be split anymore, then merges the sorted halves back together. Its time complexity of <b>O(nlogn)</b> makes it highly efficient.

- `Quick Sort:` Another "divide and conquer" powerhouse. It selects a 'pivot' element and partitions the other elements into two sub-arrays. It then recursively sorts the sub-arrays. Its average time complexity is <b>O(nlogn)</b>, making it one of the fastest sorting algorithms in practice.

## How to Run 🏃‍♂️
You don't need any special tools or servers to run this project. 
Simply download or clone the repository 
1. Visit the URL to use it:
   ```bash
    https://www.sortvisualiser-iota.vercel.app
   ```
2. Clone the repository:
   ```bash
   git clone https://github.com/ShubhamJatavBankai/sortingVisualizer.git
   cd sortingVisualizer
   run in live server or open index.html in browser window
   ```