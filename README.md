# CS221_Assignment1_Problem3

3)	Consider the binary search tree implementation available in folder N:\CLASS\GanchevG\CS221\Assignment1\BinSearchTree\
a)	Implement a member function void  printLevel(int level)that will print the values of the data members of the nodes which are at the specified level of the tree.
b)	Implement a traversal member function void postorder(Action * a) for postorder traversal of a binary search tree that carries out an action other than just printing the node data. The action should be supplied as a pointer to an object of a derived class of the class
class Action
{
  public:
	virtual void act(string str) {}
};

Use the postorder function and a suitable class derived from Action, to find the node with the largest sum of lengths of the strings stored in its children nodes. Print the node data and the sum of the lengths of the strings stored in its children nodes.
[30 points]
