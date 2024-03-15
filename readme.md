NextGenStack is a set of actively developed tools, that are build with engagemend, and wish to provide next generation developer experience and performance.
In case of this starter, brought together with Next.js

NextGenStack has :

1. Vitest for Test driven developement - https://vitest.dev/

  Allow headless unittests of all aspects of application, provided in a way that is pleasant to write.

  <code>
    test("Middleware doesn't allow access to user dashboard", async ()=>{
        expect( await middleware( new NextRequest( urlUserDashboard() )) ).toBeUndefined();
    });
  </code>

2. Drizzle ORM for relational database management - https://orm.drizzle.team/

Drizzle is written mostly in typescript, so it doesn't slow down the runtime
It behaves in a legible way, reducing all code to one sql statement.
  
