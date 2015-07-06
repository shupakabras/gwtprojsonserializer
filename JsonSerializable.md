JsonSerializable is the common interface that classes should implement in order to be serializable by the GWTProJSON Serializer.

```

class SimpleBean implement JsonSerializable {
  private String simpleAttribute;

  public SimpleBean(String value) {
    this.simpleAttribte = value;
  }
  
  public void setSimpleAttribute(String newValue) {
    this.simpleAttribute = newValue;
  }

  public String getSimpleAttribute() {
    return this.simpleAttribute;
  }
}

...

Serializer serializer =  (Serializer)GWT.create( Serializer.class );

SimpleBean simpleBean = new SimpleBean("Hello World");
String serialized = serializer.serialize(simpleBean);

System.out.println(serialized);

```