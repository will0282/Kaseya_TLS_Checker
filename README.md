# Kaseya_TLS_Checker
Displays the TLS 1.0 settings on the endpoint.

Pre-Reqs:

You need to create (4) Custom Fields (CF) in the [Audit]/[View Individual Data]/[Machine Summary].

Once the pre-reqs are completed just run this [Agent Procedure] on the desired endpoint, the (CF) will be updated.

To see the results, go to [Agent]/[Agents]/[Manage Agents] and add the following columns:

TLS 1.0\Server\DisabledByDefault

TLS 1.0\Server\Enabled

TLS 1.0\Client\DisabledByDefault

TLS 1.0\Client\Enabled
