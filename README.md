1 //GET OBJECT INDEX APEX
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


2 public class ListDemo {
   public void lisMethod(){
        List<string> str = new List<string>();		
       
       sObject sobj = [SELECT Id, Name from Account Limit 1];
       Boolean res;
        str.add('Paras');
        str.add('Raman');	
        str.add('Cheetah');
       
        system.debug('Object type  =' +sobj.getSobjectType());
        //system.debug('My name is='+str);
    }
}


3 public class ListDemo {
   public void lisMethod(){
        List<string> str = new List<string>();		
       
       sObject sobj = [SELECT Id, Name from Account Limit 1];
       Boolean res;
        str.add('Paras');
        str.add('Raman');	
        str.add('India');
       
        system.debug(str.indexof('India'));
        //system.debug('My name is='+str);
    }
}

4    public class ListDemo {
   public void lisMethod(){
        List<string> str = new List<string>();		
       
       sObject sobj = [SELECT Id, Name from Account Limit 1];
       Boolean res;
        str.add('Paras');
        str.add('Raman');	
        str.add('India');
       
        system.debug(str.isEmpty()); 
        //system.debug('My name is='+str);
        //showing false as list is not emplty
    }
}       

5
public class ListDemo {
   public void lisMethod(){
        List<string> str = new List<string>();		
       
       sObject sobj = [SELECT Id, Name from Account Limit 1];
       Boolean res;
        str.add('Paras');
        str.add('Raman');	
        str.add('India');
       
        system.debug(str.remove(1)); 
        //system.debug('My name is='+str);
        //it will remove Rama
    }
}









