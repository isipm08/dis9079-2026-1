# sesion-03

# lunes 23 marzo 2026

## HOY
+ MICROCONTROLADORES

## **Raspberry Pi**
+ Computadora (no con mouse ni teclado)
+ Desarrollo de Arduino
+ C/C++ (el que usaremos)
+ int main()
{
    stdio_init_all();

    // Initialise the Wi-Fi chip
    if (cyw43_arch_init()) {
        printf("Wi-Fi init failed\n");
        return -1;
    }

    // Example to turn on the Pico W LED
    cyw43_arch_gpio_put(CYW43_WL_GPIO_LED_PIN, 1);

    while (true) {
        printf("Hello, world!\n");
        sleep_ms(1000);
    }
}
**Mainframe**

## **Atari**

## **Commodore**

## **Spectrum Zx**

**Monty Pyton**
+ Spam
+ Lenguaje Pyton

Stdio (Standar) 
Sdk: clip de desarrollo de software 
Crash course
Mermaid (diagrama de flujo)
S1: ARDUINO ENVÍA - RASPBERRY PI RECIBE 
