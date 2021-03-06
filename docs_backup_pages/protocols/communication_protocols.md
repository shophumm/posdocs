<h3>Communication protocols</h3>

The following communication protocols are currently supported by **humm**:

* SOAP
* (non-RESTful) HTTP

If additional communication protocols are needed by POS software vendors (e.g. WebSocket), they will be added on an as-needed basis. There are also plans to implement a RESTful HTTP API. Note: REST isn't a communication protocol, rather an architectural style.

To support the SOAP communication protocol, a <a href="https://testpos.%domain%/soap/v1/TestService.svc?wsdl">WSDL</a> has been published that describes the set of **humm** endpoints.
