scala_library(name='scala',
  dependencies=[
    pants('3rdparty:swift-codec'),
    pants('3rdparty:guice'),
    pants('3rdparty:guice-multibindings'),
    pants('3rdparty:slf4j-api'),
    pants('3rdparty:thrift-0.5.0'),
    pants('finagle/finagle-core'),
    pants('finagle/finagle-thrift')
  ],
  sources=rglobs('*.scala'),
  java_sources=[pants('finagle/finagle-swift/src/main/java')],
  provides=artifact(org='com.twitter',
                    name='finagle-kestrel',
                    repo='pants-support/ivy:internal',),
)
