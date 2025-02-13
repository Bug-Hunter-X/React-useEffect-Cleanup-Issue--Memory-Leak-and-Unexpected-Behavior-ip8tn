# React useEffect Cleanup Issue

This example demonstrates a common issue in React applications involving the `useEffect` hook and data fetching.  The provided code fetches data on component mount but lacks a cleanup function to prevent potential memory leaks and unexpected behavior.  The solution shows how to properly incorporate cleanup for a more robust component.