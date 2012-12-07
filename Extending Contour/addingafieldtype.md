# Adding a field type to Umbraco Contour #

*This builds on the "adding a type to the provider model" chapter*

Add a new class to the visual studio solution and make it inherit from Umbraco.Forms.Core.FieldType and override the Editor property.

In the empty constructor add the following information:

`public Textfield() { 

//Provider 

this.Id = new Guid("D6A2C406-CF89-11DE-B075-55B055D89593 "); 

this.Name = "Textfield"; 

this.Description = "Renders a html input fieldKey"; //FieldType 

this.Icon = "textfield.png";`

}