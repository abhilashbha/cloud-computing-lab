# Experiment 4 – Salesforce Apex Application

## Aim

To develop a simple custom application using the Apex programming language on the Salesforce cloud platform.

## Procedure

1. Sign in to a Salesforce Developer Org.
2. Open the Developer Console.
3. Select **File → New → Apex Class**.
4. Create a class named `HelloWorldApp`.
5. Add a method that writes a message to the debug log.
6. Save the class.
7. Open **Debug → Open Execute Anonymous Window**.
8. Execute `HelloWorldApp.sayHello();`.
9. Open the execution log and select **Debug Only** to view the message.

## Apex Program

```apex
public class HelloWorldApp {
    public static void sayHello() {
        System.debug('WELCOME TO APEX PROGRAMMING');
    }
}
```

## Execute Anonymous

```apex
HelloWorldApp.sayHello();
```

## Expected Debug Output

```text
WELCOME TO APEX PROGRAMMING
```

## Result

A simple Apex class can be created and executed on the Salesforce cloud platform.

## Screenshots

Add actual Salesforce Developer Console screenshots when available.
