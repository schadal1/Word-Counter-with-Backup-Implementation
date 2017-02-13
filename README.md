# Word-Counter-with-Backup-Implementation
Implemented "word counter" command with Visitor, Prototype, and Observer Design Patterns 

FILES:
           
		------driver:
				  --Driver.java		  
		------dsForStrings:
				  --BackupNode.java
				  --Cloneable.java
				  --Node.java
				  --NodeInterface.java
				  --Observer.java
				  --SubjectInterface.java
				  --Tree.java
		------util:
				  --InputFileProcessor.java
				  --OutputFileProcessor.java
		------visitors:
				  --CloneAndObserverVisitor.java
				  --PopulateVisitor.java
				  --UpdateVisitor.java
				  --visitable.java
				  --Visitor.java
				  --WordCountVisitor.java
				  
				  
			
				  
				  
Input_small.txt:
***************************************************************************
Essay maps ask you to predict where your reader will expect background information Essay maps 
are not concerned with paragraphs so much as with sections of an essay They anticipate the major 
argumentative moves you expect your essay to make Try making your map like this State your thesis in a sentence or two
***************************************************************************

To verify observer pattern:

output will be displayed on the console.
The backup tree and the original tree will be the same.
Implemented fourth visitor to check the functionality of observer pattern. its working as per the implementation.
***********************************************************************

TO COMPILE:
ant -buildfile build.xml all

NOTE: Please Place the Input file parallel to the src directory

TO RUN:
Navigate to directory where build.xml is present and run 

ant -buildfile build.xml run -Darg0 smallInput.txt -Darg1 output.txt -Darg2 3

TO UN-TAR:
tar xvzf chadalla_sumanth_assign4.tar.gz


Data Structure Used:
***************************************************************************
Binary search tree : Easy to perform all operations say retrieve,remove,add.
Binary search trees are memory efficient. 
the time complexity for search,delete and retrieve are O(log n)

