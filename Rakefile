log4j_ver='2.6.2'

@files=[
  {'url' => "https://repo1.maven.org/maven2/org/apache/logging/log4j/log4j-core/#{log4j_ver}/log4j-core-#{log4j_ver}.jar", 'sha1' => '00a91369f655eb1639c6aece5c5eb5108db18306' },
  {'url' => "https://repo1.maven.org/maven2/org/apache/logging/log4j/log4j-api/#{log4j_ver}/log4j-api-#{log4j_ver}.jar", 'sha1' => 'bd1b74a5d170686362091c7cf596bbc3adf5c09b'},
  {'url' => "https://repo1.maven.org/maven2/com/lmax/disruptor/3.3.0/disruptor-3.3.0.jar", 'sha1' => '6925c7787741f6ac1535188ea450f04fa1246acf'}
]

task :default do
  system("rake -T")
end

require "logstash/devutils/rake"
