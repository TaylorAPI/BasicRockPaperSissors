using System;

namespace RockPaperSissors
{
    class Program
    {
        static void Main(string[] args)
        {


            Console.WriteLine("ROCK , PAPER, SISSORS SHOOT!"); 


            theGame g = new theGame();




            string choice = Console.ReadLine();

            g.setUserInput(choice);
            g.printResults();
           

            


        }
    }



    class theGame {



        string UserInput;
        string[] RPS = { "Rock", "Paper", "Sissors" };



        public string getUserInput()
        {


            return UserInput; 
        }


        public void setUserInput(string theInput) {

            this.UserInput = theInput; 
        
        
        
        }


        public void someLogic() {

            
            Random r = new Random();

            int AIGuesser = r.Next(RPS.Length);


            Console.WriteLine(RPS[AIGuesser]);


            if (UserInput.Contains("rock") && RPS[AIGuesser].Contains("Sissors")) {

                Console.WriteLine("Winner Rock Beats Sissors");

                
            }
            if (UserInput.Contains("rock") && RPS[AIGuesser].Contains("Paper"))
            {

                Console.WriteLine(":( Try Again Paper beats Rock" );


            }

            if (UserInput.Contains("rock") && RPS[AIGuesser].Contains("Rock"))
            {

                Console.WriteLine("Tie");


            }

            if (UserInput.Contains("paper") && RPS[AIGuesser].Contains("Rock"))
            {

                Console.WriteLine("Winner Paper Beats Rock");


            }
            if (UserInput.Contains("paper") && RPS[AIGuesser].Contains("Sissors"))
            {

                Console.WriteLine(":( Try Again Sissors beats Paper");


            }

            if (UserInput.Contains("paper") && RPS[AIGuesser].Contains("paper"))
            {

                Console.WriteLine("Tie");


            }


            if (UserInput.Contains("Sissors") && RPS[AIGuesser].Contains("Sissors"))
            {

                Console.WriteLine("Tie");


            }
            if (UserInput.Contains("Sissors") && RPS[AIGuesser].Contains("Paper"))
            {

                Console.WriteLine("Winner Sissors beats Paper");


            }

            if (UserInput.Contains("sissors") && RPS[AIGuesser].Contains("sissors"))
            {

                Console.WriteLine("Tie");


            }

        }


        public void printResults() {
            someLogic();
            
        
        }

    }


}
