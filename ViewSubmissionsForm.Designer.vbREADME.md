<Global.Microsoft.VisualBasic.CompilerServices.DesignerGenerated()> _
Partial Class ViewSubmissionsForm
    Inherits System.Windows.Forms.Form

    'Form overrides dispose to clean up the component list.
    <System.Diagnostics.DebuggerNonUserCode()> _
    Protected Overrides Sub Dispose(ByVal disposing As Boolean)
        Try
            If disposing AndAlso components IsNot Nothing Then
                components.Dispose()
            End If
        Finally
            MyBase.Dispose(disposing)
        End Try
    End Sub

    'Required by the Windows Form Designer
    Private components As System.ComponentModel.IContainer

    'NOTE: The following procedure is required by the Windows Form Designer
    'It can be modified using the Windows Form Designer.  
    'Do not modify it using the code editor.
    <System.Diagnostics.DebuggerStepThrough()> _
    Private Sub InitializeComponent()
        Me.btnPrevious = New System.Windows.Forms.Button()
        Me.btnNext = New System.Windows.Forms.Button()
        Me.lblSubmissionData = New System.Windows.Forms.Label()
        Me.SuspendLayout()
        '
        'btnPrevious
        '
        Me.btnPrevious.Location = New System.Drawing.Point(12, 226)
        Me.btnPrevious.Name = "btnPrevious"
        Me.btnPrevious.Size = New System.Drawing.Size(75, 23)
        Me.btnPrevious.TabIndex = 0
        Me.btnPrevious.Text = "Previous"
        Me.btnPrevious.UseVisualStyleBackColor = True
        '
        'btnNext
        '
        Me.btnNext.Location = New System.Drawing.Point(197, 226)
        Me.btnNext.Name = "btnNext"
        Me.btnNext.Size = New System.Drawing.Size(75, 23)
        Me.btnNext.TabIndex = 1
        Me.btnNext.Text = "Next"
        Me.btnNext.UseVisualStyleBackColor = True
        '
        'lblSubmissionData
        '
        Me.lblSubmissionData.AutoSize = True
        Me.lblSubmissionData.Location = New System.Drawing.Point(12, 9)
        Me.lblSubmissionData.Name = "lblSubmissionData"
        Me.lblSubmissionData.Size = New System.Drawing.Size(83, 13)
        Me.lblSubmissionData.TabIndex = 2
        Me.lblSubmissionData.Text = "Submission Data"
        '
        'ViewSubmissionsForm
        '
        Me.ClientSize = New System.Drawing.Size(284, 261)
        Me.Controls.Add(Me.lblSubmissionData)
        Me.Controls.Add(Me.btnNext)
        Me.Controls.Add(Me.btnPrevious)
        Me.Name = "ViewSubmissionsForm"
        Me.Text = "View Submissions"
        Me.ResumeLayout(False)
        Me.PerformLayout()

    End Sub

    Friend WithEvents btnPrevious As Button
    Friend WithEvents btnNext As Button
    Friend WithEvents lblSubmissionData As Label
End Class
