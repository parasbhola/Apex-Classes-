GET OBJECT INDEX APEX
public class ListDemo {
   public void lisMethod(){
        List<string> str = new List<string>();		  
       Boolean res;
        str.add('Paras');
        str.add('Raman');	
        str.add('Cheetah');
       
        system.debug('str =' +str.get(1));
        //system.debug('My name is='+str);
    }
} 
