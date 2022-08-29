## REVDEBUG TYPESCRIPT TUTORIAL IN REACT APP

Simple TypeScript example, click the skull button to crash and see the recordings in the flight recorder, click the error button to view the screen recordings in trace.

Configure RevDeBug repository:

    npm config set @revdebug:registry https://nexus.revdebug.com/repository/npm/

Install dependancies (including RevDeBug):

    npm install

\* Note: Before instrumenting you may need to change the "host" (and maybe "port" / "webPort") fields in "revdebug.json" or specify different values on the command line if you are not running the record server locally.

Normal instrument:

    npx revd

Or instrument passing different host:

    npx revd --host your_record_server.com

And off we go...

    npm start