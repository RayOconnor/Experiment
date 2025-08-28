# Rules for Contributing to a Fintech Payments Repository

## Test Patterns

YOU MUST NEVER use "lenient" to resolve a failing test due to "Following stubbings are unnecessary" or "Please remove unnecessary stubbings or use 'lenient' strictness."
Instead, use org.mockito.Mockito.when deliberately and only in the tests that need it.
