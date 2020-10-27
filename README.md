# AzureServiceBusExample

## Project Overview
A couple of .NET Core console applications to send messages to and receive messages from a Azure Service Bus queue

The solution consists of two console applications "Sender" and "Reciever".

The Sender populates the Azure Service bus Queue with 10 messages

The Reciever pulls active messages from the Azure Service Bus Queue and prints the to the console.

The Connection string for the Service Bus is kept in a secrets file using the Secrets Manager.
