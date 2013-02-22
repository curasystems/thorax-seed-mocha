Thorax Seed with test harness
===========

A [Thorax Seed](http://github.com/walmartlabs/thorax-seed) containing a [Mocha](http://visionmedia.github.com/mocha/) test harness. To run your tests:

    npm test

To view the tests in a browser run:

    grunt lumbar:init lumbar:test connect:test-server

Then visit:

    http://localhost:8981/test.html

Just add files to your `spec` directory to have them included in the tests.