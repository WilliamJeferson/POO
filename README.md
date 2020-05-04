package unidade_1;

//declaração da classe

public class Guitarra{
    private String numeroSerie, fabricante, modelo, tipo, madeira;
    private double preco;

    //criação do contrutor da classe Guitarra
    public Guitarra(
        String numeroSerie, String fabricante,
        String modelo,      String tipo,
        String madeira,     String preco){
            this.numeroSerie = numeroSerie;
            this.fabricante = fabricante;
            this.modelo = modelo;
            this.tipo = tipo;
            this.madeira = madeira;
            this.preco = preco;
        }
        public String getNumeroSerie(){
            return numeroSerie;
        }
        public void setNumeroSerie(String numeroSerie){
            this.numeroSerie = numeroSerie;
        }

        public String getfabricante(){
            return fabricante;
        }
        public void setfabricante(String fabricante){
            this.fabricante = fabricante;
        }

        public String getmodelo(){
            return modelo;
        }
        public void setmodelo(String modelo){
            this.modelo = modelo;
        }

        public String gettipo(){
            return tipo;
        }
        public void settipo(String tipo){
            this.tipo = tipo;
        }

        
        public String getMadeira(){
            return Madeira;
        }
        public void setMadeira(String Madeira){
            this.Madeira = Madeira;
        }

        
        public String getPreco(){
            return Preco;
        }
        public void setPreco(String Preco){
            this.Preco = Preco;
        }
        
        //o método main() é o método principal da classe
        public static void main(String[] args){
            //instanciamos um objeto chamado "minhaGuitarra" que será do tipo "Gitarra"
            //os valores assadossão usados peloconstrutor da classe para criar o objeto
            Guitarra minhaGuitarra = new Guitarra("01020304", "fender", "telecaster", "eletrica", "mogno", 1500);
            
            //testando os dados da classe, imprimindo a saída simples no terminal
            System.out.println(minhaGuitarra.getNumeroSerie());
            System.out.println(minhaGuitarra.getMadeira());
            System.out.println(minhaGuitarra.getPreco());
            System.out.println(minhaGuitarra.gettipo());
        }
    }
}
