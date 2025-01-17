# Telemetry in the CodeQL extension for VS Code

## Why do you collect data?

GitHub collects usage data and metrics to help us improve CodeQL for VS Code.

## What data is collected

GitHub collects anonymous information related to the usage of the extensions. The data collected are:

- Which commands are run.
- The time taken for each command.
- Anonymized stack trace and error message of any errors that are thrown from inside the extension.
- Anonymous GUID to uniquely identify an installation.
- IP address of the client sending the telemetry data. This IP address is not stored. It is discarded immediately after the telemetry data is received.

## How do I disable telemetry reporting?

You can disable telemetry reporting by setting `codeQL.telemetry.enableTelemetry` to `false` in [your settings](https://code.visualstudio.com/docs/getstarted/settings#_settings-editor).

Additionally, telemetry will be disabled if the global `telemetry.enableTelemetry` setting is set to `false`. For more information on global telemetry collection, see [Microsoft’s documentation](https://code.visualstudio.com/docs/supporting/faq#_how-to-disable-telemetry-reporting).
