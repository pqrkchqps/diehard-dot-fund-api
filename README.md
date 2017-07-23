# Diehard.Fund API

# Elements:
* Designer
* Builder
* Investor
* Designer Group
* Builder Group
* Investor Group

* Active Admin Comments
  * resource id
  * resource type
  * author id
  * author type
  * body
  * created at
  * updated at
  * namespace

* ahoy events
  * visit id
  * user id
  * name
  * properties
  * time

* ahoy messages
  * token
  * to
  * user id
  * user type
  * mailer
  * sent at
  * opened at
  * clicked at

* attachments
  * user id
  * filename
  * location
  * comment id
  * created at
  * updated at
  * filesize
  * file file name
  * file content type
  * file file size
  * file updated at
  * attachable id
  * attachable type

* blacklisted passwords
  * string
  * created at
  * updated at

* blog stories
  * title
  * url
  * image url
  * published at
  * created at
  * updated at

* categories
  * name
  * created at
  * updated at
  * position

* cohorts
  * start on
  * end on

* comment hierarchies
  * ancestor id
  * descendant id
  * generations

* comment votes
  * comment id
  * user id
  * created a
  * updated at

* comment
  * discussion id
  * body
  * user id
  * parent id
  * created at
  * updated at
  * uses markdown
  * comment votes count
  * attachments count
  * liker ids and names
  * edited at
  * versions count

* communities
  * community type
  * custom fields
  * created at
  * updated at
  * identity id
  * identifier

* contact messages
  * name
  * user id
  * email
  * message
  * created at
  * updated at
  * destination

* contacts
  * user id
  * name
  * email
  * source
  * created at
  * updated at

* default group covers
  * cover photo file name
  * cover photo content type
  * cover photo file size
  * cover photo updated at
  * created at
  * updated at

* delayed jobs
  * priority
  * attempts
  * handler
  * last error
  * run at
  * locked at
  * failed at
  * locked by
  * queue
  * at
  * updated at

* did not votes
  * user id
  * motion id
  * created at
  * updated at

* discussion readers
  * user id
  * created at
  * updated at
  * discussion id
  * last read at
  * read items count
  * last read sequence id
  * read salient items count  default: 0,
  * volume
  * participating
  * starred
  * dismissed at

* discussion search vectors
  * discussion id
  * search vector

* discussion tags
* discussions
* drafts
* events

* group hierarchies  id
  * ancestor id
  * descendant id  
  * generations

* group requests
  * name
  * description
  * admin email
  * created at
  * updated at
  * status
  * group id
  * cannot contribute
  * expected size
  * max size
  * robot trap
  * distribution metric
  * sectors
  * other sector
  * token
  * admin name
  * country name
  * high touch
  * approved at
  * defered until
  * approved by id
  * why do you want
  * group core purpose
  * admin notes
  * is commercial

* group visits  
  * visit id
  * group id
  * created at
  * updated at
  * user id
  * member

* groups  
  * name
  * created at
  * updated at
  * parent id
  * description
  * memberships count
  * archived at
  * discussions count
  * full name
  * parent members can see discussions
  * key
  * category id
  * subdomain
  * theme id
  * is visible to public
  * is visible to parent members
  * discussion privacy options
  * members can add members
  * membership granted upon
  * members can edit discussions
  * motions can be edited
  * cover photo file name
  * cover photo content type
  * cover photo file size
  * cover photo updated at
  * logo file name
  * logo content type
  * logo file size
  * logo updated at
  * members can edit comments
  * members can raise motions
  * members can vote
  * can start discussions
  * members can create subgroups
  * creator id
  * is referral
  * cohort id
  * default group cover id
  * subscription id
  * motions count
  * invitations count
  * admin memberships count
  * public discussions count
  * country
  * region
  * city
  * closed motions count
  * enable experiments
  * analytics enabled
  * proposal outcomes count
  * experiences
  * pending invitations count
  * features
  * recent activity count
  * community id
  * closed polls count
  * announcement recipients count
  * polls count
  * subgroups count

* invitations
  * recipient email
  * inviter id
  * to be admin
  * token
  * accepted at
  * intent
  * canceller id
  * cancelled at
  * recipient name   limit: 255
  * invitable id
  * invitable type   limit: 255
  * created at
  * updated at
  * single use
  * message
  * send count

* login tokens
  * user id
  * token
  * used
  * created at
  * updated at
  * redirect

* membership requests
  * name
  * email
  * introduction
  * group id
  * created at
  * updated at
  * requestor id
  * responder id
  * response
  * responded at

* memberships
  * group id
  * user id
  * created at
  * updated at
  * inviter id
  * archived at
  * inbox position
  * admin
  * is suspended
  * volume
  * experiences

* motion readers
  * motion id
  * user id
  * created at
  * updated at
  * last read at
  * read votes count
  * read activity count  default: 0, null: false

* motions
  * name
  * description
  * author id
  * created at
  * updated at
  * closed at
  * discussion id
  * outcome
  * last vote at
  * yes votes count
  * no votes count
  * abstain votes count
  * block votes count
  * closing at
  * votes count
  * outcome author id
  * key
  * members count
  * voters count

* network coordinators
  * coordinator id
  * network id
  * created at
  * updated at

* network membership requests
  * requestor id
  * responder id
  * group id
  * network id
  * approved
  * message
  * created at
  * updated at

* network memberships
  * group id
  * network id
  * created at
  * updated at

* networks
  * name
  * slug
  * description
  * joining criteria
  * created at
  * updated at

* notifications
  * user id
  * created at
  * updated at
  * event id
  * viewed
  * translation values  default: {},
  * url
  * actor id
  * actor type

* oauth access grants
  * resource owner id
  * application id
  * token
  * expires in
  * redirect uri
  * created at
  * revoked at
  * scopes

* oauth access tokens
  * resource owner id
  * application id
  * token
  * refresh token
  * expires in
  * revoked at
  * created at
  * scopes

* oauth applications
  * name
  * uid
  * secret
  * redirect uri
  * scopes
  * created at
  * updated at
  * owner id
  * owner type
  * logo file name
  * logo content type
  * logo file size
  * logo updated at

* omniauth identities
  * user id
  * email
  * created at
  * updated at
  * identity type  limit: 255
  * uid
  * name
  * access token
  * logo
  * custom fields

* organisation visits
  * visit id
  * organisation id
  * created at
  * updated at
  * user id
  * member

* outcomes
  * poll id
  * statement
  * author id
  * created at
  * updated at
  * latest
  * poll option id
  * custom fields

* poll communities
  * poll id
  * community id

* poll did not votes
  * poll id
  * user id
  * poll options  
  * name
  * poll id
  * priority

* poll references
  * reference id
  * reference type
  * poll id

* poll unsubscriptions
  * poll id
  * user id
  * created at
  * updated at

* polls
  * author id
  * title
  * details
  * closing at
  * closed at
  * created at
  * updated at
  * discussion id
  * key
  * poll type
  * motion id
  * stance data
  * stances count
  * multiple choice
  * custom fields
  * stance counts
  * group id
  * matrix counts
  * notify on participate
  * visitors count
  * example
  * undecided user count
  * undecided visitor count  default: 0,
  * voter can add options

* stance choices
  * stance id
  * poll option id
  * score
  * created at
  * updated at

* stances
  * poll id
  * participant id
  * participant type
  * reason
  * latest
  * created at
  * updated at

* subscriptions
  * kind
  * expires at
  * trial ended at
  * activated at
  * chargify subscription id
  * plan
  * payment method

* tags
  * group id
  * name
  * color
  * created at
  * updated at
  * discussion tags count  default: 0

* themes
  * style
  * name
  * created at
  * updated at
  * pages logo file name
  * pages logo content type  limit: 255
  * pages logo file size
  * pages logo updated at
  * app logo file name
  * app logo content type
  * app logo file size
  * app logo updated at
  * javascript

* translations
  * translatable id
  * translatable type  limit: 255
  * fields
  * language
  * created at
  * updated at

* user deactivation responses
  * user id
  * body

* users
  * email
  * encrypted password
  * reset password token
  * reset password sent at
  * remember created at
  * sign in count
  * current sign in at
  * last sign in at
  * current sign in ip
  * last sign in ip
  * created at
  * updated at
  * name
  * deactivated at
  * is admin
  * avatar kind
  * uploaded avatar file name
  * uploaded avatar content type
  * uploaded avatar file size
  * uploaded avatar updated at
  * avatar initials
  * username
  * email when proposal closing soon
  * authentication token
  * unsubscribe token
  * memberships count
  * uses markdown
  * selected locale
  * time zone
  * key
  * detected locale
  * email missed yesterday
  * email api key
  * email when mentioned
  * angular ui enabled
  * email on participation
  * default membership volume
  * country
  * region
  * city
  * experiences
  * facebook community id
  * slack community id
  * remember token
  * short bio

* versions
  * item type
  * item id
  * event
  * whodunnit
  * object
  * created at
  * object changes

* visitors
  * participation token
  * name
  * email
  * created at
  * updated at
  * avatar kind
  * avatar initials
  * community id
  * revoked

  * visits  id
  * visitor id
  * ip
  * user agent
  * referrer
  * landing page
  * user id
  * referring domain
  * search keyword
  * browser
  * os
  * device type
  * screen height
  * screen width
  * country
  * region
  * city
  * utm source
  * utm medium
  * utm term
  * utm content
  * utm campaign
  * started at

* votes
  * motion id
  * user id
  * position
  * created at
  * updated at
  * statement
  * age
  * previous vote id

* webhooks
  * hookable id
  * hookable type
  * kind
  * uri
  * event types
