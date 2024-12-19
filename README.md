# Asynchronous Update in useState Hook

This example demonstrates a common misconception about the `useState` hook in React. Because state updates are asynchronous, accessing the state value immediately after calling `setCount` might not reflect the updated value.