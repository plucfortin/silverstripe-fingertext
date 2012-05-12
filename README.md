silverstripe-fingertext
=======================

Silverstripe Code Snippets for FingerText Notepad++ plugin


INSTALLATION:

1.	Install the FingerText plugin for Notepad++ :
	
	Open the plugin manager:
	"Plugins" menu -> "Plugin Manager" ->  "Show Plugin Manager".
	
	In the "Available" tab of the plugin manager window,
	check the "FingerText" plugin.
	
	Click the "Install" button.
	
2.	Open the FingerText "SnippetDock" :

	"Plugins" menu -> "FingerText" -> "Toggle On/off SnippetDock"
	
3.	Open the Snippet Editor.

	In the SnippetDock, there should be an "Open Snippet Editor" Button.
	
4.	Import the PHP code snippet file.

	Click on the "Import ftd file" button.
	
	Select the "silverstripe.php.ftd" file, 
	which is located at the root of this repository.
	
5.	Import the SS code snippet file.

	Click on the "Import ftd file" button.
	
	Select the "silverstripe.ss.ftd file, 
	which is located at the root of this repository.
	
6.	Then live a happy life.


HOW TO USE:

	USING PHP SNIPPETS:
	
	1. Open a new file.
	
	2. Ensure that this file in PHP language. To do that:
		"Language" menu -> "P" -> "PHP".
		
		Now, the PHP code snippets are available.
		
	3. Place your cursor somewhere in the file and 
	   write a snippet tag, then hit the "TAB" key on your keyboard.
	
		For example, write "dataobject" (without the quotes), then
		hit the "TAB" button.
		
		If done well, the "dataobject" keyword will be replaced
		with a lot of code representing the skeleton of a DataObject
		subclass.
		
	4. There are many other code
	
	USING SS SNIPPETS:
	
	1. You use the SS code snippets the same way you use the
	   PHP code snippets, except that you have to work in a
	   .ss file where the language is set to ASP.
	   
	   The reason for that is that .ss syntax highlighting is
	   not defined in Notepad++. However, the .asp syntax is
	   very similar to the .ss syntax. So .asp syntax highlighting
	   works well with .ss files.
	   
	   So, if, for the file you are working on, you set the
	   language to ASP, then the .ss snippets will become available
	   with the "TAB" key.
	   
	EXPLORING EXISTING SNIPPETS:
	
	1. You should explore all the available snippets to be efficient.
	
		To do that, open a file in PHP or ASP language. Then, open 
		the SnippetDock. If you are in PHP file, you should see 
		a list of all the PHP snippet keywords.
		
		Then, you can see the content, edit it, or add it 
		to the file you are working on.
		
		You can also modify these snippets, or create new ones if
		you wish.
		
FINGERTEXT PLUGIN FOR NOTEPAD++

	1. The FingerText plugin for Notepad++ has its own repository
	   on Github:
	   
	   https://github.com/erinata/FingerText
	   
	   The README.rdoc file contains a lot of further useful
	   explanations on how to use FingerText.