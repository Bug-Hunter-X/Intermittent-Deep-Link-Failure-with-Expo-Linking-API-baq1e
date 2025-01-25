# Expo Linking API Intermittent Deep Link Failure

This repository demonstrates a bug related to the Expo Linking API's handling of deep links, specifically involving custom URL schemes. The app sometimes fails to register or respond to incoming deep links, resulting in unpredictable behavior. The solution provided addresses potential causes and offers strategies for robust deep link handling.

## Bug Description

The app intermittently fails to open when a deep link with a custom URL scheme is used.  This problem is non-deterministic and difficult to track down consistently.

## Solution

The `bugSolution.js` file provides a revised implementation of the deep link handling that includes strategies to mitigate the potential causes of this intermittent failure.  These strategies include more thorough error handling and improved URL scheme registration.