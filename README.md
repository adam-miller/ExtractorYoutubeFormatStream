ExtractorYoutubeFormatStream
============================

Youtube video extractor processor for heritrix3. Checks a youtube watch page for a JSON object containing the list of available video formats, and adds them as outlinks.

Build: mvn -Dmaven.test.skip=false clean install
Result: target/ExtractorYoutubeFormatStream-0.1.jar
