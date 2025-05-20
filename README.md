Quiz_Using_2DArray created on July 2023

import java.util.Scanner;

public class QuizUsing2DArray {
    static Scanner input = new Scanner(System.in);

    public static void Quizeasy() {
        int correct = 0;
        int incorrect = 0;
        int questions = 10;
        System.out.println("Easy Quiz");
        String[][] Quest_ans = {
                {
                        "What is the biggest state in Peninsular Malaysia?",
                        "\n A.Sarawak \n B.Pahang \n C.Johor \n D.Perlis",
                        "B"
                },
                {
                        "Which city situated in the south is the nearest to Singapore?",
                        "\n A.Malacca City \n B.Shah Alam \n C.Iskandar Puteri \n D.Johor Bahru",
                        "D"
                },
                {
                        "What is the dominant religion of Malaysia?",
                        "\n A.Hinduism \n B.Buddhism \n C.Islam \n D.Christianity",
                        "C"
                },
                {
                        "The famous hill resort Genting Highlands is located in which state?",
                        "\n A.Pahang \n B.Perak \n C.Selangor \n D.Kelantan",
                        "A"
                },
                {
                        "What is the smallest state in Malaysia?",
                        "\n A.Perlis \n B.Selangor \n C.Kedah \n D.Perak",
                        "A"
                },
                {
                        "What date does our independence day?",
                        "\n A.9 August 1965 \n B.17 August 1945 \n C.16 September 1963 \n D.31 August 1957",
                        "D"
                },
                {
                        "What money currency does Malaysia use?",
                        "\n A.THB \n B.IDR \n C.SGD \n D.MYR",
                        "D"
                },
                {
                        "Sabah and Sarawak is often called by the name of the large island these states rest upon, which is what?",
                        "\n A.Borneo \n B.Madagascar \n C.Honshu \n D.Sumatra",
                        "A"
                },
                {
                        "What is Malaysia's central bank?",
                        "\n A.Bank Negara Malaysia \n B.Exim Bank \n C.Bank Pertanian Malaysia \n D.Sabah Bank Berhad",
                        "A"
                },
                {
                        "What is the largest flower in Malaysia?",
                        "\n A.Bougainvillea \n B.Orchids \n C.Hibiscus \n D.Rafflesia",
                        "D"
                }
        };
        String[] user_ans = new String[(int) questions];
        int i = 0;
        do {
            System.out.println(" " + (i + 1) + "." + Quest_ans[i][0] + " " + Quest_ans[i][1]);
            user_ans[i] = String.valueOf(input.next().charAt(0));
            if (Quest_ans[i][2].equals(user_ans[i].toUpperCase())) {
                System.out.println("Correct Answer!");
                correct++;
            } else {
                System.out.println("Incorrect !");
                incorrect++;
            }
            i++;
        } while (i < questions);
        System.out.println("-----------RESULT-------------");
        System.out.println("Total incorrect:" + incorrect);
        System.out.println(correct + "/" + questions);
    }

    public static void Quizmedium() {
        int correct = 0;
        int incorrect = 0;
        int questions = 10;
        System.out.println("Medium Quiz");
        String[][] Quest_ans = {
                {
                        "In which specific part of the world is Malaysia?",
                        "\n A.South West Asia \n B.West Europe \n C.Southeast Asia \n D.North Africa",
                        "C"
                },
                {
                        "What is the longest river in Malaysia?",
                        "\n A.Kinabatangan River \n B.Rajang River \n C.Pahang River \n D.Perak River",
                        "B"
                },
                {
                        "Which state with the nickname \"Land below the Wind\"",
                        "\n A.Sabah \n B.Johor \n C.Kedah \n D.Pahang ",
                        "A"
                },
                {
                        "What is the name of the largest cave chamber in Malaysia?",
                        "\n A.Perak Cave \n B.Dark Cave \n C.Clearwater Cave \n D.Gua Niah",
                        "D"
                },
                {
                        "Malaysia is a country of great economy and infrastructure due in part to what adjacent waterway,a great boon to their shipping industry?",
                        "\n A.Strait of Hormuz \n B.Strait of Malacca \n C.Sunda Strait \n D.Makassar Strait",
                        "B"
                },
                {
                        "What is the national dish of Malaysia?",
                        "\n A.Rendang \n B.Asam Laksa \n C.Nasi lemak \n D.Nasi kerabu",
                        "C"
                },
                {
                        "Which sea separates Peninsular Malaysia from Sabah and Sarawak?",
                        "\n A.South China Sea \n B.Philippine Sea \n C.Malaysia Sea \n D.Asia Sea",
                        "A"
                },
                {
                        "What is the most famous fruit in Malaysia?",
                        "\n A.Durian \n B.Rambutan \n C.Cempedak \n D.Langsat",
                        "A"
                },
                {
                        "The southwest coast of Malaysia is not so clear from May to September; the northeast from November to March."
                                +
                                "This is because Malaysia has two seasons of which weather phenomenon?",
                        "\n A.Dust storm \n B.Blizzard \n C.Earthquake \n D.Monsoon",
                        "D"
                },
                {
                        "What is the tallest mountain in Malaysia?",
                        "\n A.Mount Trusmadi \n B.Mount Kinabalu \n C.Mount Sinsing \n D.Mount Tambuyukon",
                        "B"
                }
        };
        String[] user_ans = new String[(int) questions];
        int i = 0;
        do {
            System.out.println(" " + (i + 1) + "." + Quest_ans[i][0] + " " + Quest_ans[i][1]);
            user_ans[i] = String.valueOf(input.next().charAt(0));
            if (Quest_ans[i][2].equals(user_ans[i].toUpperCase())) {
                System.out.println("Correct Answer!");
                correct++;
            } else {
                System.out.println("Incorrect !");
                incorrect++;
            }
            i++;
        } while (i < questions);
        System.out.println("-----------RESULT-------------");
        System.out.println("Total Correct:" + correct);
        System.out.println("Total incorrect:" + incorrect);
        System.out.println(correct + "/" + questions);
    }

        public static void Quizhard() {
        int correct = 0;
        int incorrect = 0;
        int questions = 10;
        System.out.println("Hard Quiz");
        String[][] Quest_ans = {
        {
        "Sultan Abu Bakar, who was known as \"The Father of Modern Johor\"," +
        "ruled Johor from 1862 to 1895 and was a lifelong friend of which monarch of the United Kingdom?",
        "\n A.Queen Victoria \n B.King Edward VII \n C.King George IV \n D.Queen Elizabeth I", "A"
        },
        {
        "What food that's originated in Malaysia?",
        "\n A.Mohinga Rice \n B.Chicken Chop \n C.Nasi Uduk \n D.Som Tam",
        "B"
        },
        {
        "Malaysia is blessed with an abundance of natural resources. In the late 1970s and early 1980s, Malaysia was known to be " +
        "one of the world's top producers of which silvery mineral, that is synonymous with pewter and its manufacturer Royal Selangor?",
        "\n A.Gold \n B.Lead \n C.Tin \n D.Zinc ",
        "C"
        },
        {
        "Who is the famous designer/shoemaker in Malaysia?",
        "\n A.Dato Lewré Lew Fong Voon \n B.Christy Ng \n C.Jimmy Choo \n D.Mohd Faizol ",
        "C"
        },
        {
        "Malaysia is the home of the first ever budget airline in South East Asia. Which budget airline was it?",
        "\n A.Air South East Asia \n B.Tiger Airways \n C.Air Asia \n D.Air Malaysia",
        "C"
        },
        {
        "How many stories does the Petronas Twin Towers has?",
        "\n A.88 \n B.118 \n C.95 \n D.74",
        "A"
        },
        {
        "Johor Bahru is connected to Singapore via two bridges.What is the one,that's opened to traffic in 1998 named?",
        "\n A.The Second Link \n B.The Causeway II \n C.The New Bridge \n D.The Crossing",
        "A"
        },
        {
        "What is Malaysia’s national bird?",
        "\n A.Oriental Pied Hornbill \n B.Wreathed Hornbill \n C.Rhino hornbills \n D.Great Hornbill",
        "C"
        },
        {
        "In Pahang, you can find the second largest natural lake in Malaysia.According to legend, " +
        "a dragon dwells at the bottom of the lake and an ancient city lies in its depths.",
        "\n A.Tasik Bera \n B.Tasik Chini \n C.Cameron Highlands \n D.Genting Highlands",
        "B"
        },
        {
        " Malaysia is classified as 'megadiverse', referring to which aspect of its population?",
        "\n A.Its cultural heritage \n B.Its ex-patriated citizens \n C.Its regional climates \n D. Its endemic species",
        "D"
        }
        };
        String[] user_ans = new String[(int) questions];
        int i = 0;
        do {
        System.out.println(" " + (i + 1) + "." + Quest_ans[i][0] + " " + Quest_ans[i][1]);
        user_ans[i] = String.valueOf(input.next().charAt(0));
        if (Quest_ans[i][2].equals(user_ans[i].toUpperCase())) {
        System.out.println("Correct Answer!");
        correct++;
        } else {
        System.out.println("Incorrect !");
        incorrect++;
        }
        i++;
        }
        while (i < questions);
        System.out.println("-----------RESULT-------------");
        System.out.println("Total Correct Answer:" + correct);
        System.out.println("Total Incorrect Answer:" + incorrect);
        System.out.println(correct + "/" + questions);
        }

    public static void main(String[] args) {
        Scanner Quest = new Scanner(System.in);
        System.out.println("Please choose Difficulty\n E-Easy \n M-Medium \n H-Hard \n ");
        char q = Quest.next().charAt(0);
        switch (q) {
            case 'E' -> {
                Quizeasy();
            }
            case 'M' -> {
                Quizmedium();
            }
            case 'H' -> {
                Quizhard();
            }
            default -> {
                System.out.println("invalid input");
            }
        }
    }
}
