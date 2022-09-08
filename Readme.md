## Purpose

This solution is to demo how Masstransit Routing slips should help ensuring distributed transaction across services.

## Initial Scope

### Success flow

- Trigger routing slip activities
- All 3 services success process with console log

### Failed on second service

- Trigger routing slip activities
- Exception throw on second service
- Compensation activity was trigger for first and second service with console log

### Failed on third service

- Trigger routing slip activities
- Exception throw on third service
- Compensation activity was trigger for all 3 services with console log

## References

- [Masstransit Courier](https://masstransit-project.com/advanced/courier/)
- [Building routing slip](https://masstransit-project.com/advanced/courier/builder.html)