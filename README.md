# Myprogram.exe

    Sub Main()
        Dim BankBalance As Single = 500.01
        If (BankBalance < 0) Then
            Dim strError As String
            strError = "Hey, your bank balance is negative!"
            System.Console.WriteLine(strError)
        End If
    End Sub
