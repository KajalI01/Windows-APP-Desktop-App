# Windows-APP-Desktop-App
Public Class MainForm
    Private Sub btnCreateNew_Click(sender As Object, e As EventArgs) Handles btnCreateNew.Click
        Dim createForm As New CreateForm()
        createForm.Show()
    End Sub

    Private Sub btnView_Click(sender As Object, e As EventArgs) Handles btnView.Click
        Dim viewForm As New ViewForm()
        viewForm.Show()
    End Sub
End Class

