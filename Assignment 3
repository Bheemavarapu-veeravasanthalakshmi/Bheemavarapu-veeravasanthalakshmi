class organization implements Cloneable{  
int organization no;  
String name;  
  
organization(int orgno,String name){  
this.orgno=orgno;  
this.orgname=orgname;  
}  
  
public Object clone()throws CloneNotSupportedException{  
return super.clone();  
}  
  
public static void main(String args[]){  
try{  
organization 1=new organization(1,"oo");  
  
organization 2=(organization)1.clone();  
  
System.out.println(1.orgno+" "+1.name);  
System.out.println(2.orgno" "+2.name);  
  
}catch(CloneNotSupportedException c){}  
  
}  
}  
