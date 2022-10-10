//Hotel-Management-Application version 1.0

import java.util.Scanner;
public class HotelMenu{
    public static void menu(int x){
       switch (x) {
        case 1:
            System.out.println("Order Received - Shhahi Paneer.Your order will be prepared in next 25 min.\n*****Be Patient*****");
            break;
        case 2:
            System.out.println("Order Received - Chhole.Your order will be prepared in next 25 min.\n*****Be Patient*****");
            break;
        case 3:
            System.out.println("Order Received - Dal Makhni.Your order will be prepared in next 25 min.\n*****Be Patient*****");
            break;
        case 4:
            System.out.println("Order Received - Kadhai Paneer.Your order will be prepared in next 25 min.\n*****Be Patient*****");
            break;
        case 5:
            System.out.println("Order Received - Malai Chaap.Your order will be prepared in next 25 min.\n*****Be Patient*****");
            break;
        case 6:
            System.out.println("Order Received - Biryani.Your order will be prepared in next 25 min.\n*****Be Patient*****");
            break;
        case 7:
            System.out.println("Order Received - Paav Bhaji.Your order will be prepared in next 25 min.\n*****Be Patient*****");
            break;
        case 8:
            System.out.println("Order Received - Chhole Bhature.Your order will be prepared in next 25 min.\n*****Be Patient*****");
            break;
        case 9:
            System.out.println("Order Received - Idli Sambhar.Your order will be prepared in next 25 min.\n*****Be Patient*****");
            break;
        case 10:
            System.out.println("Order Received - Masala Dosa.Your order will be prepared in next 25 min.\n*****Be Patient*****");
            break;
        default:
        System.out.println("Invalid Input");
            break;
       }
    }
    public static void main(String[] args) {
        Scanner sc = new Scanner(System.in);
        System.out.println("The menu of this hotel is as follows:-\n1.Shahi Paneer\t 240/-\n2.Chhole\t 120/-\n3.Dal Makhni\t 120/-\n4.Kadhai Paneer\t 280/-\n5.Malai Chaap\t 200/-\n6.Biryani\t 150/-\n7.Paav Bhaaji\t 100/-\n8.Chhole Bhature 100/-\n9.Idli Sambhar\t 110/-\n10.Masala Dosa\t 120/-.\nPlease enter the dish number from the menu:");
        int m = sc.nextInt();
        HotelMenu obj = new HotelMenu();
        obj.menu(m);
    }
}
