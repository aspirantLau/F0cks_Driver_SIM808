# F0cks_Driver_SIM808

## How to use this library

1. You need to create files like "sim.c" and "sim.h".
2. In those files, you need to implement several functions:
	* void F0cks_Delay_ms(uint32_t ms);
	* void F0cks_SIM808_PWRKEY_High(void);
	* void F0cks_SIM808_PWRKEY_Low(void);
	* void F0cks_SIM808_UART_Send(char *string);

## Release description

* v0.0.2 : 13/02/2018
	* Reworking word parser: prevent overflow, parse all words in one function
	* Create a function to store battery DATA
	* Create a function to start GMS
	* Create a function to start GPRS
	* Create a function to send SMS

* v0.0.1 : 09/02/2018
	* Create functions needed start and stop SIM808 module