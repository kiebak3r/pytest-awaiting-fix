# Welcome to pytest-awaiting-fix

A simple plugin to use with pytest which helps retain traceability between automated tests and Jira statuses.
When a test is tagged with the @pytest.mark.awaiting_fix('test') decorator it will automatically skip this test
and comment which disabled automation tests are associated to the ticket
