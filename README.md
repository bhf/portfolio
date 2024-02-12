# Samples of Work by Technology Type


Below are examples of where I've worked with different technologies:

**Agrona RingBuffer**


[IdentifyingManyToOneRingBuffer](https://github.com/bhf/marketdata-messages/blob/main/src/main/java/com/bht/md/ringbuffers/IdentifyingManyToOneRingBuffer.java)

[SBEToAgronaIdentifiableRingbufferFragmentHandler](https://github.com/bhf/marketdata-messages/blob/main/src/main/java/com/bht/md/rbpublishers/SBEToAgronaIdentifiableRingbufferFragmentHandler.java)

[SBEToAgronaRingbufferFragmentHandler](https://github.com/bhf/marketdata-messages/blob/main/src/main/java/com/bht/md/rbpublishers/SBEToAgronaRingbufferFragmentHandler.java)

[AgronaMessageHandler](https://github.com/bhf/marketdata-messages/blob/main/src/main/java/com/bht/md/rbhandler/AgronaMessageHandler.java)

[AgronaSBEDecodingHandler](https://github.com/bhf/marketdata-messages/blob/main/src/main/java/com/bht/md/rbhandler/AgronaSBEDecodingHandler.java)

[IdentifiableAgronaMessageHandler](https://github.com/bhf/marketdata-messages/blob/main/src/main/java/com/bht/md/rbhandler/IdentifiableAgronaMessageHandler.java)

[IdentifiableAgronaSBEDecodingHandler](https://github.com/bhf/marketdata-messages/blob/main/src/main/java/com/bht/md/rbhandler/IdentifiableAgronaSBEDecodingHandler.java)




**Disruptor**


[DisruptorSBEDecodingHandler](https://github.com/bhf/marketdata-messages/blob/main/src/main/java/com/bht/md/rbhandler/DisruptorSBEDecodingHandler.java)

[SBEToDisruptorFragmentHandler](https://github.com/bhf/marketdata-messages/blob/main/src/main/java/com/bht/md/rbpublishers/SBEToDisruptorFragmentHandler.java)



**Aeron**


[marketdata-messages project](https://github.com/bhf/marketdata-messages)

[AeronPublisher](https://github.com/bhf/marketdata-messages/blob/main/src/main/java/com/bht/md/aeron/AeronPublisher.java)

[AeronSubscriber](https://github.com/bhf/marketdata-messages/blob/main/src/main/java/com/bht/md/aeron/AeronSubscriber.java)




**Chronicle Queue**


[ChronicleSBEDecodingHandler](https://github.com/bhf/marketdata-messages/blob/main/src/main/java/com/bht/md/rbhandler/ChronicleSBEDecodingHandler.java)

[SBEToChronicleQueueFragmentHandler](https://github.com/bhf/marketdata-messages/blob/main/src/main/java/com/bht/md/rbpublishers/SBEToChronicleQueueFragmentHandler.java)

[BufferMarshallable](https://github.com/bhf/marketdata-messages/blob/main/src/main/java/com/bht/md/rbpublishers/BufferMarshallable.java)

[ChronicleBasedPerfManager](https://github.com/bhf/marketdata-messages/blob/main/src/main/java/com/bht/md/perfmeta/ChronicleBasedPerfManager.java)

[perfMeta.*Marshallable](https://github.com/bhf/marketdata-messages/tree/main/src/main/java/com/bht/md/perfmeta)


**SBE Message Encoding and Decoding**

[handlers.AbstractSBEDecodingHandler](https://github.com/bhf/marketdata-messages/blob/main/src/main/java/com/bht/md/handlers/AbstractSBEDecodingHandler.java)

[handlers.SBEDecodingHandler](https://github.com/bhf/marketdata-messages/blob/main/src/main/java/com/bht/md/handlers/SBEDecodingHandler.java)

[encodehelpers.*](https://github.com/bhf/marketdata-messages/tree/main/src/main/java/com/bht/md/messages/encodehelpers)

[sendhelpers.*](https://github.com/bhf/marketdata-messages/tree/main/src/main/java/com/bht/md/messages/sendhelpers)



**Likwid Markers**

[JMH Test as part of comparing marked and unmarked performance](https://github.com/bhf/jmh-playground/blob/main/src/main/java/com/bhf/averages/CalculatingAveragesLikwid.java)

[AbstractMarkedSBEDecodingHandler](https://github.com/bhf/marketdata-messages/blob/main/src/main/java/com/bht/md/handlers/AbstractMarkedSBEDecodingHandler.java)


**HDRHistogram**

[MessageBasedRTHistogramRecorder](https://github.com/bhf/marketdata-messages/blob/main/src/main/java/com/bht/md/handlers/MessageBasedRTHistogramRecorder.java)



**ThreadAffinity**

[ThreadFactoryUtil](https://github.com/bhf/marketdata-messages/blob/main/src/main/java/com/bht/md/util/ThreadFactoryUtil.java)


**Unit testing**

[Encoder Decoder chain testing](https://github.com/bhf/encoder-chain-testing)


**JMH benchmarking**

[Benchmark process development, array averaging performance and cache behaviour](https://github.com/bhf/jmh-playground)
