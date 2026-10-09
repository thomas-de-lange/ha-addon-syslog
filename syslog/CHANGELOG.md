# Changelog

## 0.4.3 (Fork thomas-de-lange)

- Fix: RFC3164 timestamp with space-padded day ("Oct  9" instead of "Oct 09"), otherwise Grafana Alloy drops all messages on days 1-9 of each month

## 0.4.2 (Fork thomas-de-lange)

- Fix: no trailing NUL byte, so RFC3164 parsers like Grafana Alloy no longer drop every message (mib1185/ha-addon-syslog#39, #40 by @hkoeck)
- Fork: no prebuilt image, Home Assistant builds the add-on locally from the Dockerfile

## 0.4.1

- Fix tagging of containers

## 0.4.0

- Handle unavailable syslog server

## 0.3.0

- Add tls support

## 0.2.0

- Determine correct syslog level for ha core, supervisor and haos host messages

## 0.1.0

- Use pre-built images

## 0.0.2

- Make messages RFC3164 (bsd) compliant

## 0.0.1

- Initial version
