# Write-VstsAddAttachment
[table of contents](../Commands.md#toc) | [brief](../Commands.md#write-vstsaddattachment)
```
NAME
    Write-VstsAddAttachment

SYNOPSIS
    See https://github.com/Microsoft/vso-agent-tasks/blob/master/docs/authoring/commands.md

SYNTAX
    Write-VstsAddAttachment [-Type] <String> [-Name] <String> [-Path] <String> [-AsOutput]
    [<CommonParameters>]

PARAMETERS
    -Type <String>

        Required?                    true
        Position?                    1
        Default value
        Accept pipeline input?       false
        Accept wildcard characters?  false

    -Name <String>

        Required?                    true
        Position?                    2
        Default value
        Accept pipeline input?       false
        Accept wildcard characters?  false

    -Path <String>

        Required?                    true
        Position?                    3
        Default value
        Accept pipeline input?       false
        Accept wildcard characters?  false

    -AsOutput [<SwitchParameter>]
        Indicates whether to write the logging command directly to the host or to the output pipeline.

        Required?                    false
        Position?                    named
        Default value                False
        Accept pipeline input?       false
        Accept wildcard characters?  false

    <CommonParameters>
        This cmdlet supports the common parameters: Verbose, Debug,
        ErrorAction, ErrorVariable, WarningAction, WarningVariable,
        OutBuffer, PipelineVariable, and OutVariable. For more information, see
        about_CommonParameters (https://go.microsoft.com/fwlink/?LinkID=113216).
```
