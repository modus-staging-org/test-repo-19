# Fix flaky test in the scheduler suite

Transient upstream 5xx responses now retry three times with exponential backoff and jitter.

Change #1 of 4 on branch `pr/20260811-130203-1-fix-flaky-test-in-the-scheduler-suite`.
