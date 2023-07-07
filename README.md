//Binary tree
//Binary tree is the tree data structure in which each node can have at most two children i.e. left child and right child.
//Binary tree is the hierarchical in structure which is top most node called as root node and bottom nodea are called as leaves of binary tree
//Structure of binary tree is shown below.
/*struct Node{
int data;
Node*leftChild;
Node *rightChild;
};*/
//method using class.
/*class Node{
public:
int data;
Node*leftChild;
Node *rightChild;
};*/
//Implementation of Binary tree.
#include <bits/stdc++.h>
using namespace std;

class Node {
public:
	int data;
	Node* left;
	Node* right;
	Node(int val)
	{
		data = val;
		left = NULL;
		right = NULL;
	}
};

int main()
{
	Node* root = new Node(1);//root node
	root->left = new Node(2);//left node
	root->right = new Node(3);//right node

	root->left->left = new Node(4);//left of left node
	
	return 0;
}



