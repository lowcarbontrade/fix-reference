# FIX Protocol JSON Schemas Definitions

Welcome to the Low Carbon Trade repository for Financial Information eXchange (FIX) protocol JSON schemas. This repository contains the JSON schema definitions for various FIX messages, customized and used by Low Carbon Trade to ensure robust and standardized financial communications.

## FIX Protocol

The Financial Information eXchange (FIX) protocol is an electronic communications protocol initiated in 1992 for international real-time exchange of information related to securities transactions and markets. With trillions of dollars traded annually on the NASDAQ alone, financial service entities are investing heavily in optimizing electronic trading and employing direct market access (DMA) to increase their speed to financial markets. The FIX protocol is a way to digitize communications between financial entities, and is the de facto standard for pre-trade, trade, and post-trade communications.

## Definitions

### Header

The header is the first section of a FIX message. It contains the basic information about the message, including the sender, target, and message type. The header is always the first section of a FIX message.

### Logon Message (35=A)

The logon message is used to establish a connection between two parties and exchange basic information. It is the first message sent by the initiator of a FIX session to the target. The logon message is used to establish a connection between two parties and exchange basic information. It is the first message sent by the initiator of a FIX session to the target after establishing the transport layer connection.

### Pre-Trade Messages

> Soon to be added

### Trade Messages

#### New Order - Single (35=D)

The new order - single message type is used by institutions wishing to electronically submit securities and forex orders to a broker for execution. The message type is also used to cancel, replace, or restate orders. The new order message type is the basic message for submitting orders into the system.

#### Order Cancel Request (35=F)

The order cancel request message type is used by institutions wishing to cancel previously submitted orders. There is no order cancel replace request message type. To change the parameters of an order, the order must be cancelled and a new order must be entered.

### Post-Trade Messages

> Soon to be added