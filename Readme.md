<======================================= CLEEN =======================================> 

CLEEN is an Social Meidia App where users can share spare or extra stuff they don't need or no longer use. 

This App aims to reduce the amount of still usable stuff and eatable food that goes to the landfill while assisting the one in need. 


A person who is either looking for a specific item and cannot afford to buy it and those who have who want to give things away will create an account. Businesses can also create an account and allow charity organization to pick up their waste.

A user can do the following
Post what he/she has and would like to give away.
Confirm his need or interest in the item available by checking the need button.
 Comment on the post
Notification is sent to the post owner and other people who commented on a post
Post owner can delete a comment as well as comment owner. 
other users can respond to a comment, tag, and flag it as well. (available emoji reaction)
Share information about places where other people can find stuff free or at a very low cost (not ads)
Post other useful content that can help improve their community

User Profile
	A user profile (User Object) will contain: 
	Name
	Email
	Username
	Password
	Posts {Object}
	Comments {object} - Belongs to a user and linked a post

User Post
	A post will have: 
		Author
		Post Date time
		Post Comments

Groups
	A group will contain
		Group Admin
		Members
		Posts
		Comment 
		Time Stamp
		
	
**************************************************** Process **************************************************** 
                                        ****&&&****User access the App or website ****&&&****
                                        Home page : shows tag line
                                ===================================================================
                                = Sign in =>Open sign page || Sign up button => opepn sign up page= 
                                ===================================================================

**************************************************** Sing Up Page **************************************************** 
            
                    ===================================================================================
                    =                                                                                 =
                    =                               ========Sign up Form========                      =
                    ===================================================================================

                    ===================================================================================
                    =                                                                                 =
                    =                               ========Sign in Form========                      =
                    ===================================================================================

****************************************************  Objects **************************************************** 

        User{
            id:"string"
            useranem:"String",
            FirstName: "String",
            LastName: "String",
            email: "email"
            password: "password"
            date stamp: date, 
            posts:{contains post objects},
            comments:{ comment object objects},
            account history:{}
        }

        Post{
            postId:"string",
            post image: "image URL"(not required),
            post description/notes: "string",(required)
            Author:"string - who post it - should show up under the user's data",
            time stamp: {},
        }

        Comment {
            id:"",
            commentText:"",
            Author:"string",
            Post:"the post the comment was made on"
        }




