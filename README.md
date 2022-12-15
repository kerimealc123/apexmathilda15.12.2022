# apexmathilda15.12.2022

//control class kodlar
system.debug(control.tekcift(5));
System.debug(control.tekcift(88));

System.debug(control.login('kerime@com', 8989));
System.debug(control.weather(-3));

string gelensonuc=control.login('kerime@com', 8989);

System.debug(gelensonuc);
control.topla(9,8);
control.topla(6,89);
control.msg();


//Erisim class kodlar
Erisim k=new Erisim();
System.debug(k.sayi);

System.debug(Erisim.name); //obje olusturdugum icin age degerini getirdi
Erisim y=new Erisim();     // obje olusturmadan static yazmadan degeri getiremem
System.debug(y.age);

System.debug(Erisim.a);


// erisim class
public class Erisim {
    
    public  integer sayi=88;
    public static String name='seyma';
    public String age='98';
    private String a='mirza';
}


//control class

public class control {
    
    public static String tekcift(integer sayi){
        integer sonuc=math.mod(sayi,2);
        if(sonuc==0){
            return 'cift';
          
        }else{
         return 'tek';
        }
        
    }

 public static String login (String mail, Integer password){
    if(mail=='kerime@com' && password==8989){
        return 'basarili';
    }else{
     return   'lutfen tekrar deneyiniz';
    }
}

    public static String weather(Integer derece){
        if(derece<0){
            return 'cold';
        }else{
            return 'warm';
        }
    }
    public static void Topla(Integer a, Integer b){
        integer sum= a+b;
        System.debug(sum);
    }
    public static void msg(){
        System.debug('apex');
    }
    
}
public class control {
    
    public static String tekcift(integer sayi){
        integer sonuc=math.mod(sayi,2);
        if(sonuc==0){
            return 'cift';
          
        }else{
         return 'tek';
        }
        
    }

 public static String login (String mail, Integer password){
    if(mail=='kerime@com' && password==8989){
        return 'basarili';
    }else{
     return   'lutfen tekrar deneyiniz';
    }
}

    public static String weather(Integer derece){
        if(derece<0){
            return 'cold';
        }else{
            return 'warm';
        }
    }
    public static void Topla(Integer a, Integer b){
        integer sum= a+b;
        System.debug(sum);
    }
    public static void msg(){
        System.debug('apex');
    }
    
}

public class control {
    
    public static String tekcift(integer sayi){
        integer sonuc=math.mod(sayi,2);
        if(sonuc==0){
            return 'cift';
          
        }else{
         return 'tek';
        }
        
    }

 public static String login (String mail, Integer password){
    if(mail=='kerime@com' && password==8989){
        return 'basarili';
    }else{
     return   'lutfen tekrar deneyiniz';
    }
}

    public static String weather(Integer derece){
        if(derece<0){
            return 'cold';
        }else{
            return 'warm';
        }
    }
    public static void Topla(Integer a, Integer b){
        integer sum= a+b;
        System.debug(sum);
    }
    public static void msg(){
        System.debug('apex');
    }
    
}

public class control {
    
    public static String tekcift(integer sayi){
        integer sonuc=math.mod(sayi,2);
        if(sonuc==0){
            return 'cift';
          
        }else{
         return 'tek';
        }
        
    }

 public static String login (String mail, Integer password){
    if(mail=='kerime@com' && password==8989){
        return 'basarili';
    }else{
     return   'lutfen tekrar deneyiniz';
    }
}

    public static String weather(Integer derece){
        if(derece<0){
            return 'cold';
        }else{
            return 'warm';
        }
    }
    public static void Topla(Integer a, Integer b){
        integer sum= a+b;
        System.debug(sum);
    }
    public static void msg(){
        System.debug('apex');
    }
    
}

public class control {
    
    public static String tekcift(integer sayi){
        integer sonuc=math.mod(sayi,2);
        if(sonuc==0){
            return 'cift';
          
        }else{
         return 'tek';
        }
        
    }

 public static String login (String mail, Integer password){
    if(mail=='kerime@com' && password==8989){
        return 'basarili';
    }else{
     return   'lutfen tekrar deneyiniz';
    }
}

    public static String weather(Integer derece){
        if(derece<0){
            return 'cold';
        }else{
            return 'warm';
        }
    }
    public static void Topla(Integer a, Integer b){
        integer sum= a+b;
        System.debug(sum);
    }
    public static void msg(){
        System.debug('apex');
    }
    
}

