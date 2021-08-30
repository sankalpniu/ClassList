# ClassList
Software Engineering

Map<String,String> classList = new Hashmap<String,String>();
public classGrades(){
classList.put("Bob","A");
classList.put("Mary","C");
classList.put("Sarah","B");
classList.put("Philip","A");
classList.put("Greg","F");
}
public void ClassList(){
Iterator<Entry<String,String>> entries=classList.entrySet().iterator();
while(entries.hasNext())
{
Entry<String,String> entry=entries.next();
System.out.println("Key = " +entry.getKey() + ", Value = " + entry.getvalue());
}
}
public void ClassList2(){
for(Map.Entry<String,String> entry:classList.entryset())
{
System.out.println("Key = " +entry.getKey() + ", Value = " + entry.getvalue());
}
for(String key : classList.keySet()){
System.out.println("key =" +key);
}
for(String value : classList.values()){
System.out.println("Value =" +value);
}
}

public static void main(String[] args){
ClassGrades myClassList= new classGrades();
myClassList.printClassList();

}
