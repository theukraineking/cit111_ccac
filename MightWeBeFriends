package week5;

import java.util.Scanner;

/**
 *Program to find if compatible with friend
 * compatability score
 * @author Dennis
 */
//public class
public class MightWeBeFriends {
    //creating a compat threshold to determine score
    final static int COMPAT_THRESHOLD = 100;
    //creating PVSM
    public static void main(String[] args){
        //creating variables to store data
        int compatScore = 0;
        int responseNum = 0;
        //New scanner named scan
        Scanner scan = new Scanner(System.in);
        //Introduciton and asks user 1st question
        System.out.println("Hello Friend, looking to find a compatable friend?");
        System.out.println("**************************************");
        System.out.println("Question 1: Do you play video games?");
        System.out.println("Yes = 1; No = 0");
        // uses scanner for inputs
        responseNum = scan.nextInt();
        // if responses
        if(responseNum == 1){
            System.out.println("****************************");
            System.out.println("NICE!");
            //Then asks user what games they play after asking if they play video games
            //gives them score for playing video games
            compatScore = compatScore + 50;
            System.out.println("What games do you play?");
            System.out.println("League of Legends = 1");
            System.out.println("MineCraft = 2");
            System.out.println("Any Shooter game = 3");
            System.out.println("Farming game = 4");
            System.out.println("Mobile Games = 5");
            System.out.println("Other = 6");
            //gets user response
            responseNum = scan.nextInt();
            System.out.println("***********************");
            //gets all responses
            if(responseNum == 1){
                System.out.println("Nice Dood, final question");
                compatScore = compatScore + 30;
            } else if(responseNum ==2){
                System.out.println("Kinda a yikes but not terrible, final question");
                compatScore = compatScore - 1;
            } else if(responseNum ==3){
                System.out.println("Respectable, final question");
                compatScore = compatScore + 20;
            } else if(responseNum == 4){
                System.out.println("A good mind numbing game, final question");
                compatScore = compatScore + 10;
            } else if(responseNum == 5){
                System.out.println("Get a computer or console, final question");
                compatScore = compatScore  -20;
            } else if(responseNum == 6){
                System.out.println("Explorer type I see, final question");
                compatScore = compatScore +1;
            }
        }else {
            //if didnt like video games
            System.out.println("********************************************************");
            System.out.println("No games well then I guess we will go to question 3");
            
        }
        //asks final question and most important question
        System.out.println("Question 3: Do you play bass guitar?");
        // tells the inputs
        System.out.println("Yes = 1; No = 0");
        responseNum = scan.nextInt();
        if(responseNum == 1){
            System.out.println("Mad Respect");
            compatScore = compatScore + 100;
        } else {
            System.out.println("Feel the rythym and get one!");
            compatScore = compatScore - 40;
        } 
        // display user scores
        System.out.println("Your compatability sore is:  ");
        System.out.println("compatScore");
        System.out.println("Out of 100:");
        System.out.println(COMPAT_THRESHOLD);
                
        //final friend compat determination
        if(compatScore >= COMPAT_THRESHOLD){
            System.out.println("Determination: Friends it is!!!!!!!!!!");
        } else {
            System.out.println("Determination: GG friend maybe next time");
        }
        System.out.println("See you next time");
    }
}
     
