- 👋 Hi, I’m @surafelseboka
- 👀 I’m interested in ...
- 🌱 I’m currently learning ...
- 💞️ I’m looking to collaborate on ...
- 📫 How to reach me ...

<!---
surafelseboka/surafelseboka is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->


public void addAtBeginning(String data){
        Node node = new Node(data);
        if(this.head==null)
        	this.head=this.tail=node;
        else
        	node.setNext(this.head);
        	this.head=node;        
	}
