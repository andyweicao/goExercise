# Approach

Split current directory path and target directory path separated by "/" into string arrays. Traverse currentPathArray and targetPathArray and store the file names by using an extra array called result. If current file name is ".", skip it. If current file name is "..", remove last file name in the result array. Then append each file name left in result array with "/". Time complexity is O(n) and space is O(n).