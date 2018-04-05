public class aulaAtividades{
            public static void main(String[] args){
                int[] idades = new int[3];
                String[] nomes = new String[3];
                int idade = 0;
                int idadeMaior = 0;
                String nomeIdadeMaior = "";
                for (int i = 0; i<=2; i++) {
                    nomes[i] = JOptionPane.showInputDialog("Digite o seu nome");
                    idades[i] = Integer.parseInt(JOptionPane.showInputDialog("Digite sua idade"));
                    idade = idades[i];
                    /*if (nomes[i] == "fim"){
                        break;
                    }*/
                    if (idade > idadeMaior){
                        idadeMaior= idade;
                        nomeIdadeMaior = nomes[i];
                    } else{
                      }
                }
                System.out.println("Pessoa com a maior idade\nNome: "+nomeIdadeMaior+" Idade: "+idadeMaior);
            }
        }
