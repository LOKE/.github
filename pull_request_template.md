Describe what this change means for non-engineering|Documentation only|Internal change only

## Submitter Checklist

Check only those that apply to this change.

- [ ] Self-reviewed code, removed extraneous comments, debug logging, checked code style
- [ ] No change to users after merge (off-by-default configuration, feature flag, alt URL, etc.) and can be disabled if issues arise (if this is not the case we may need stakeholder signoff)
- [ ] Changes are documented (README, wiki, etc)
- [ ] Automated tests added
- [ ] Manually tested changes
- [ ] Metrics added to track the usage/performance
- [ ] I am confident I can revert this change
- [ ] Database migrations are reversible without data loss (if applicable)
- [ ] Performance impact is acceptable (if applicable)
- [ ] Any new dependencies are justified or have been approved (if applicable)
- [ ] **This is NOT a high risk change** (if it is, please follow the high-risk change process)

### Testing Evidence

What evidence supports that you have tested this change?

- [ ] Test cases cover the new functionality or changes
- [ ] Screenshots or logs of the changes (if applicable)
- [ ] Performance benchmarks (if applicable)
- [ ] Storybook cases (if applicable)

## Reviewer Checklist

Note: if this PR affects authentication or payments please seek a secondary tester.

- [ ] I am ok with code style and functionality
- [ ] I have personally tested the feature
- [ ] My review was not rushed due to time constraints
