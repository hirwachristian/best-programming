Q1.
Logging refers to the process of recording program execution events, messages, and information, such as errors, warnings, debugging data, and audit trails, to a file, database, or console.

Q2.

i Debugging and Troubleshooting: Logs help developers understand what the application was doing when an issue occurred, making it easier to identify and fix bugs.

ii User Support:Logs aid support teams in diagnosing and resolving issues by providing detailed information about the problem's context when reported by users.

iii Operational Insights: Logs provide valuable insights into application usage patterns, aiding organizations in making informed decisions about scaling, feature development, and resource allocation.

iv Monitoring and Maintenance: Logs provide insights into the application's behavior over time, allowing for proactive maintenance and performance tuning.

Q3.
Logging levels categorize messages based on severity or importance, aiding in filtering and prioritizing them, with common levels ranging from most severe to least severe:

i FATAL: Indicates a severe error that will prevent the application from continuing to run. Immediate attention is required.
Example: System crash.

ii ERROR: Signifies an error that might allow the application to continue running but indicates a problem that should be fixed.
Example: Null pointer exceptions.

iii WARN: Represents a warning that something unexpected happened or might cause problems in the future. The application continues to run, but caution is advised.
Example: Deprecated API usage.

iv INFO: Provides informational messages that highlight the progress of the application at a coarse-grained level. Useful for tracking the flow of the application
Example: Application start/stop.

v DEBUG: Used for detailed diagnostic information to help developers troubleshoot issues. These messages are usually only needed during development.
Example: Variable values.

vi TRACE: Offers the most detailed level of logging, providing fine-grained informational events. Typically used for tracing the execution of code at a very detailed level.
Example: Entering and exiting functions.