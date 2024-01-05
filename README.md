# teste-dos-bichos   
package animaisfauna;

/**
 *
 * @author RicardoViana962
*/
public static void main(String[] args) {      
        


    public class AnimaisFauna {
    protected int ID;
    protected String nome;
    public AnimaisFauna(int ID, String nome){
        this.ID = ID;
        this.nome = nome;
    }
    public int getID(){return ID;}
    public String getNome(){return nome;}

    public class Terrestre extends AnimaisFauna{
        private int getID;

        public Terrestre(int ID, String nome) {
            super(ID, nome);
        }
        public void teste(){
            String nome = getNome();
            int id = getID;
            System.out.println("ID:"+id+"Nome:"+nome);
            
        }
    
    }
    
    

   
 
    }
    
    
}

