# Part-of-the-system-for-a-restaurant
package com.company;

import jdk.swing.interop.SwingInterOpUtils;

import java.util.Scanner;

public class Main
{
    static float order(float total)
    {
        return total;
    }
    static float order(float total,int deliveryCosts)
    {
        return total+deliveryCosts;
    }
    static float order(float total,int deliveryCosts,String promo)
    {
        return total+deliveryCosts-2;
    }


    public static void main (String args[])
    {
        System.out.println(order(15,3,"asfk"));

    }
}



