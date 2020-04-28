# virality

**language used** 
  python3

**Creating a code which checks the probability of some information getting viral**

**This is what the code does**
  *takes in a string of 20 characters or less
  *takes in the hyper parameters for the deep neural network
  *gives out the virality score of the input string out of 100

**This is what how the code does what is does**
  *takes the information (headlines) from archives of thetimesofindia.com in the form of list which contains the headlines of the no of days mentioned from today
  *send that information to google as a search and from the search results, take the number of hits, which is saved as an list (each corresponding to its headline)
  *Use these two lists to create a deep learning network of about 3 hidden layers , where the first layer contains ascii representations of each letter of the headline, and the output corresponds to the no of hits on google
  *this output is then neutralized and scaled by comparing it to the maximum value in the extracted dataset
