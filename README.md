  
public class GFG { 
    public static void main(String[] args) 
    { 
        // Create an empty hash map 
        HashMap<String, Integer> map 
            = new HashMap<>(); 
  
        // Add elements to the map 
        map.put("vishal", 10); 
        map.put("sachin", 30); 
        map.put("vaibhav", 20); 
  
        // Print size and content 
        System.out.println("Size of map is:- "
                           + map.size()); 
        System.out.println(map); 
  
        // Check if a key is present and if 
        // present, print value 
        if (map.containsKey("vishal")) { 
            Integer a = map.get("vishal"); 
            System.out.println("value for key"
                               + " \"vishal\" is:- "
                               + a); 
        } 
    } 
} 
Output:
Size of map is:- 3
{vaibhav=20, vishal=10, sachin=30}
value for key "vishal" is:- 10
Traversal of HashMap


filter_none
edit
play_arrow

brightness_4
// Java program to illustrate 
// Java.util.HashMap 
  
import java.util.HashMap; 
import java.util.Map; 
  

