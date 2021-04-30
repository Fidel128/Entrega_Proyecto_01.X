Entrega_Proyecto_01.X
/*
 * File:   LED.c
 * Author: fidel
 *
 * Created on 30 de abril de 2021, 01:27 PM
 */
/*RODRIGUEZ MALDONADO FIDEL ANTONIO 7CV7*/
#define F_CPU 1000000UL
#include <util/delay.h>
#include <avr/io.h>

int main(void) {
    /* Replace with your application code */
    
        DDRC=0xFF;
        
    while (1) {
        
    
    PORTC=0xC0;
    _delay_loop_2(90000);
    PORTC=0x00;
    _delay_loop_2(90000);
        
    }
}
