# Vuetify (VCalendar Warnings)

The current repository contains minimal code to duplicate the warning messages. If the example codes from Usage section of the Calendar component in the labs page is used, more of the warning errors are thrown.

## Install & Preview
```sh
cd vuetify-project;
bun install;
bun run dev;
```

With any of the following versions of browser below, navigate to http://localhost:3000 for minimal reproduction of the warnings or http://localhost:3000/more for more warnings.
- Google Chrome v140.0.7+
- Microsoft Edge v140.0.3+
- FireFox v143.0.1+

## Example (Minimal Warning)
```
[Vue warn]: Failed to resolve directive: resize 
  at <VCalendar> 
  at <VApp> 
  at <App>
```

## Example (Extended Warnings)
```
[Vue warn]: Failed to resolve directive: ripple 
  at <VCalendarWeekly ref=Ref< 
Proxy { <target>: {…}, <handler>: {…} }
 > class="v-calendar v-calendar-events" role="grid"  ... > 
  at <VCalendar ref="calendar" modelValue="" onUpdate:modelValue=fn  ... > 
  at <VSheet height="600" > 
  at <Index onVnodeUnmounted=fn<onVnodeUnmounted> ref=Ref< 
Proxy { <target>: {…}, <handler>: {…} }
 > > 
  at <RouterView> 
  at <VMain> 
  at <Default onVnodeUnmounted=fn<onVnodeUnmounted> ref=Ref< 
Proxy { <target>: Proxy, <handler>: {…} }
 > > 
  at <RouterView> 
  at <VApp> 
  at <App> runtime-core.esm-bundler.js:51:13
[Vue warn]: Failed to resolve directive: ripple 
  at <VCalendarWeekly ref=Ref< 
Proxy { <target>: {…}, <handler>: {…} }
 > class="v-calendar v-calendar-events" role="grid"  ... > 
  at <VCalendar ref="calendar" modelValue="" onUpdate:modelValue=fn  ... > 
  at <VSheet height="600" > 
  at <Index onVnodeUnmounted=fn<onVnodeUnmounted> ref=Ref< 
Proxy { <target>: {…}, <handler>: {…} }
 > > 
  at <RouterView> 
  at <VMain> 
  at <Default onVnodeUnmounted=fn<onVnodeUnmounted> ref=Ref< 
Proxy { <target>: Proxy, <handler>: {…} }
 > > 
  at <RouterView> 
  at <VApp> 
  at <App> runtime-core.esm-bundler.js:51:13
[Vue warn]: Failed to resolve directive: ripple 
  at <VCalendarWeekly ref=Ref< 
Proxy { <target>: {…}, <handler>: {…} }
 > class="v-calendar v-calendar-events" role="grid"  ... > 
  at <VCalendar ref="calendar" modelValue="" onUpdate:modelValue=fn  ... > 
  at <VSheet height="600" > 
  at <Index onVnodeUnmounted=fn<onVnodeUnmounted> ref=Ref< 
Proxy { <target>: {…}, <handler>: {…} }
 > > 
  at <RouterView> 
  at <VMain> 
  at <Default onVnodeUnmounted=fn<onVnodeUnmounted> ref=Ref< 
Proxy { <target>: Proxy, <handler>: {…} }
 > > 
  at <RouterView> 
  at <VApp> 
  at <App>
```

