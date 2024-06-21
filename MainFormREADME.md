Public Class MainForm
    Private Sub btnViewSubmissions_Click(sender As Object, e As EventArgs) Handles btnViewSubmissions.Click
        ' Dummy data for testing
        Dim submissions As New List(Of String) From {
            "Name: John Doe, Email: john@example.com, Phone: 1234567890, GitHub: github.com/johndoe, Time: 00:05:23",
            "Name: Jane Smith, Email: jane@example.com, Phone: 0987654321, GitHub: github.com/janesmith, Time: 00:10:15"
        }

        Dim viewForm As New ViewSubmissionsForm(submissions)
        viewForm.Show()
    End Sub

    Private Sub btnCreateSubmission_Click(sender As Object, e As EventArgs) Handles btnCreateSubmission.Click
        Dim createForm As New CreateSubmissionForm()
        createForm.Show()
    End Sub
End Class
