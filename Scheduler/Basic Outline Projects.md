- need [oauth implementation](https://atproto.com/specs/oauth) to allow users to log into the service
- need to be able to create scheduled tasks for particular scheduled items
	- probably will make a custom lexicon for holding the scheduled task
	- certain items should probably not be publicly viewable so it'll have to be centrally stored in lack of private records

what to do first:
- post a record to a PDS after auth'ing a user ([look into oauth](https://atproto.com/specs/oauth) first tho).
	- just use some temp fake record for now lel
- 
## Lexicon Defs
```json
"dev.jeanmachine.scheduler" : {
	
}
```