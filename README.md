# AsciiTable4j
AsciiTable4j is a Minimalistic Ascii Table Generator for Java

	*********************************************************
	Description : 
	.........................................................
	
	AsciiTable4j is a Minimalistic Ascii Table Generator for Java
	@author Jonathan Vanhouteghem - http://vanhouteghem-jonathan.fr/
	Last edit : 2016-03-19
	

	*********************************************************
	Using example : 
	.........................................................
	
	AsciiTable4j t = new AsciiTable4j();
		
	// create table
	t.addRow(Arrays.asList("Name", "Age", "Hobbies", "Married"));
	t.addRow(Arrays.asList("John", "22", "KravMaga", "No"));
	t.addRow(Arrays.asList("Alexandra", "28", "Painting", "No"));
	t.addRow(Arrays.asList("Quentin", "32", "Running", "Yes"));
	t.addRow(Arrays.asList("Sebastien", "36", "VideoGames", "Yes"));
	t.addRow(Arrays.asList("Jeanine", "60", "Sew", "Yes"));
		
	// show table
	t.showTable(); 
	
	*********************************************************
	Output : 
	.........................................................

	| Name      | Age | Hobbies    | Married |
	------------------------------------------
	| John      | 22  | KravMaga   | No      |
	| Alexandra | 28  | Painting   | No      |
	| Quentin   | 32  | Running    | Yes     |
	| Sebastien | 36  | VideoGames | Yes     |
	| Jeanine   | 60  | Sew        | Yes     |
	
	*********************************************************
