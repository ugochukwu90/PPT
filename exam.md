```py
START
 IF temperature > 30 THEN
            OUTPUT "Alert High temperature"
            highTempCount = highTempCount + 1
        END IF
    END  
    
    FOR day = 1 TO 7
        INPUT temperature
        CALL checkTemperature(temperature)
    END FOR

    OUTPUT "Number of days with high temperature: ", highTempCount
END

```



```py
START
  checkPassword(inputPassword)
 IF inputPassword = "secure123" THEN
            RETURN TRUE
        ELSE
         OUTPUT "Incorrect password. Try again."
            RETURN FALSE
        END IF
    END 

    DO
        OUTPUT "Enter password:"
        INPUT password
        valid = checkPassword(password)
    WHILE valid = FALSE

    OUTPUT "Access granted."
END
```

```py
START
sellTicket
 OUTPUT "Ticket sold"
  END 

   OUTPUT "Enter number of tickets to sell:"
    INPUT ticketCount

    FOR i = 1 TO ticketCount
        CALL sellTicket
    END FOR

    OUTPUT "All tickets sold"
END

```

