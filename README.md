# TextAnalysisAgent

0:00: Hi team, I'm, I'm myself, and today I'm going to cover a brief demo about what Omni is, and then we will do a team type of doing some hands-on work using Omni for dashboard. 
 0:09: So let's start the video. 
 0:11: First of all, what actually Omni means a very fascinating, right? 
 0:14: So Omni is nothing but a BI analytics tool which was created by locals co-founders. 
 0:17: Looker was one of the most widely used tools for VI and data analytics in its time. 
 0:22: So only has been created by local co-founders. 
 0:25: So it means that it is having one of the best functionalities which look already had, and even. 
 0:29: It has many more things added. 
 0:31: So O is built for keeping business users in mind so that a data team having various types of personalities or technical backgrounds can come in all together and build one of the most useful dashboard which the CEO actually sees, right? 
 0:42: So let's say for example a person is good at Excel, so he can also build the requirements and things for his own use cases, whereas if someone is good at doing SQL queries, like all the analysts, they love SQL queries, so they can directly write. 
 0:52: Those ports and see. 
 0:53: Let's say if there is an account executive which is just seeing your dashboard just before the presentation a few hours ago, and he finds that there can be some tweaks that can be made to the dashboard before sharing it to the CEO. 
 1:02: So you can really go in and use some quick cals, AI related features or some drag and drop optionality so that you can also get into those. 
 1:09: So basically only can be used by any type of, technical user or business user depending on what actually he wants to build. 
 1:14: So that's something. 
 1:15: Which is a really great feature. 
 1:17: Other than that, Omni's philosophy is building on, there's a keyword called on-time data modeling. 
 1:22: So yeah, that will sound a little bit weird to a lot of data engineers and analytics engineers to make sure that the best practices we've already defined all those data models before we even go to the final goal layers or the BI layers, right? 
 1:33: But yeah, there can be use cases where the on-time data modeling approach can be much better. 
 1:37: Like especially I would say in cases where. 
 1:39: We have data as a product, right, and where the data gets changed very frequently where the data modeling is still evolving as the data product evolves, right, it is not a fixed type of model and the business team is still thinking of what are the important metrics that we can use. 
 1:50: So those are the times when only on-time modeling is really useful. 
 1:53: When I say one time modeling simply means that we can build the data modeling only as we progress towards creating our dashboard or creating our business requirements along with what's say. 
 2:03: Thinking and having a discussion with the user. 
 2:05: Let's say for example I'm having a meeting with my CEO or any other data engineer with my team, I can, or any account executive, and I can build the dashboard on time along with the data models with them on their metric requirements and upon their dimensions and needs, etc. 
 2:18: where we don't, I don't have to define the data model before like fixing all the silver layers and transformations. 
 2:22: So that's something really cool. 
 2:23: So how does only does that, right? 
 2:25: So I have a snapshot presented which I can show for how only actually does that. 
 2:30: So. 
 2:32: Yeah, so this is my screen and I have a good architecturedup which I stole from the Omni's website itself. 
 2:37: It can help me can help you explain what actually what data means. 
 2:40: So simply as you see that we have a raw database schema and then on top of it only has its own shared or workbook model type of approach. 
 2:47: And then once we have the workbook models, all these changes that we do are stored in this workbook. 
 2:50: And then after that we can move it and promote it to our final shared module, which shared model you can see, see it is the final. 
 2:56: On the layer of data cement modeling for only where everything that you push into that shared model is accessible by all users. 
 3:02: Like, for example, I create a new metric called sales value, and I'm just keeping it in my own, workbook model. 
 3:07: So it's just, being used by me and no other user can see that. 
 3:10: And when I promote it to the shared model, then, any other user who creates a new workbook or they can see that sales count as a metric directly in those books. 
 3:17: So that's a very useful feature where we can build our data models depending on what metric. 
 3:21: etc. 
 3:22: we want and apparel, let's say on time, modeling can happen at the same time and multiple and the work on different things we can then build those boards basically for like the best DevOps practice where we can have it integrated and the branch mode, etc. 
 3:33: I will be going in detail with all these topics after that as well when I share the demo of the working presentation. 
 3:39: So let me hop on to the dashboard which I've created, and I can give a quick overview of how things actually look like and what can only, right? 
 3:46: So. 
 3:47: This is a revenue analytics snack show for an e-commerce company where we have data for e-commerce, etc. 
 3:52: like the sales, what are the products, the average order values, the total number of orders, the net sales, the high value orders, scatter blot, etc. 
 3:59: So this is how the interface of Uni looks like, where you can create all those dashboards, and every dashboard, it's connected to a workbook. 
 4:04: What you can see is nothing but a place where you actually create those standard. 
 4:07: and measures and we build these awesome looking charts. 
 4:10: Yeah, so let's go behind the scenes and see how this works. 
 4:13: And for that I can also tell you some quick filters related functionalities. 
 4:17: Let's say we have some basic filters of,, let's say time related, daytime change filters, for example, if I have to change the time of my entire dashboard from months to weeks or maybe even days, I can simply do that. 
 4:27: With the click, right, let's change it to E. 
 4:29: So all the dashboards or tiles which are connected to this particular filter, they automatically get up updated, right, as you see, the net sales were converted to weeks, the orders, the conversion rate, I don't think that it's going to be calculated on the basis of week, so it's not showing in the top 10 products for weeks. 
 4:39: Then you, the net sales is having the historical, yeah, excesses on weeks. 
 4:43: This looks really great, right? 
 4:44: Similarly, if I want to go back to month, I can switch it back and I'll have monthly. 
 4:49: So there you'll be seeing there's another thing just towards the right of this created that feature. 
 4:52: This is called parent control, right? 
 4:54: So what does parent control means? 
 4:55: It basically means that all. 
 4:56: Parent and child relationship but you all you all know exactly so all the Filters which are of similar kind, like for example, similar data filters, etc. 
 5:04: you can club those together with the parent and so all those will be synced with the parent control. 
 5:08: For example, let's say if I have to update this month to week, then all the daytime related filters which are linked to this particular parent control will automatically get upgraded to weeks. 
 5:15: Similarly if I update this to date, all these filters will get automatically updated to date. 
 5:18: That's a huge advantage when we have multiple data related filters and we want to change those. 
 5:22: So how do we do that actually? 
 5:23: It's quite simple. 
 5:24: We just have to select what are the child controls, for example, right now this was not applicable yet, Let's see if I have to move this created art filter in the parent. 
 5:33: So what's the label here? 
 5:33: It's all created art. 
 5:34: We can copy and paste it. 
 5:35: We can do update this, and then we can do the parent control and we can quickly look at what are the children. 
 5:41: So I see that the children I can still create at at label. 
 5:44: So all the label filters where the label is created at will become the children of this parent control. 
 5:48: And whenever things are updated here, they'll automatically get updated in those children, yeah, that's really cool feature. 
 5:53: So here I create selected created at my default values month. 
 5:56: I done all the options I've already selected, and let's say I move this month to week. 
 6:00: In this automatically converted into week then we can hide this or this filter so that all the changes can be done with just a single click for all these different dates. 
 6:07: This is a great feature, right? 
 6:08: So we have one feature which is called field changes. 
 6:11: Let's say for example, here you are seeing that we are seeing top 10 products on the basis of category jeans, pants, softwares, etc. 
 6:17: But let's say the user wants to see it on the basis of the brand, right? 
 6:20: What which brand is more famous, either Levi's or something else, so. 
 6:23: How does it quickly does that? 
 6:24: So we can quickly go to the filter and can update this date. 
 6:26: What's it. 
 6:27: What's the name of this filter? 
 6:28: I let me quickly check that multi-il with the sorry field which is the filter, and we can easily convert this. 
 6:33: So let's say here right now I'm selected category. 
 6:35: So whichever tiles are connected to this filter. 
 6:37: If I move them to brand, then simply attach to those tiles will get updated, yeah, as you see, now we are seeing the top end brands here. 
 6:43: Levi's at top, yeah, that was my guess. 
 6:45: Then we have Rayban, Vumbia, etc. 
 6:46: etc. 
 6:47: Solarly as you see the scatter plots present here, that also got changed, right? 
 6:49: It means that this is also connected to this. 
 6:50: This is a really, really useful feature. 
 6:53: And we don't have to create multiple charts of save type where the fields are different. 
 6:57: We can directly use a field picker and we can combine all those similar charts together and at the time of dashboarding or presenting, we can simply change those fields. 
 7:04: So how do we do that? 
 7:05: That's also very simple and easy. 
 7:06: We have to go to this add control tab. 
 7:07: We have to add a field switcher. 
 7:09: It will automatically be created. 
 7:10: We have to select the columns which we need. 
 7:11: Let's say for example, right now I'm in my data modeling layer. 
 7:14: I have to add the products called called brand. 
 7:16: I add that then. 
 7:18: It will show here. 
 7:19: Similarly, I have to add another option. 
 7:22: let's go to distribution center's name. 
 7:23: So these are basically locations and these are all in the charts which I guess in what's it. 
 7:26: , what's the world getting updated or getting changed with these filter? 
 7:31: I selected 10, if to use brand, and let's say now if I update this brand to name, all these will automatically change to him. 
 7:37: Yeah, that's how easy it is. 
 7:40: I that back, otherwise it will mess my dashboard. 
 7:42: I have two filters on the same fields. 
 7:44: Yeah, name. 
 7:46: So the expected thing is here it should be changed to name, right? 
 7:49: Los Angeles. 
 7:49: So our top products are being sold in Los Angeles. 
 7:51: So that's all our top selling locations at Los Angeles, and we have Chicago, and etc. 
 7:55: etc. 
 7:55: Yeah, we also see the latter got here. 
 7:57: This is a great filter. 
 7:59: Another some cool things are like the multivalue filters where I can select the top 10 places, records on top, I would say 50 products, etc. 
 8:07: So doing this is also quite simple. 
 8:09: I will show you the back end of this one second again. 
 8:11: We will move deeper to the modeling layer and the workbook layer of things. 
 8:14: And what else do we have? 
 8:15: Yeah, so let's cover those things one by one. 
 8:17: Let me go to the workbook actually showing you the behind the scenes of this overall dashboard, how these things work and how you can also build these. 
 8:24: There's one more thing before that I would like to show you. 
 8:25: I was talking about the different branch modes, right, like the integrations, etc. 
 8:28: So as you can see right now, I am my developer branch. 
 8:31: So all these changes are currently present in my branch, the way. 
 8:33: Happens in software engineering or data engineering, right? 
 8:35: If I have to promote these changes to the main branch of the state, which in the production, so I have to promote these changes. 
 8:39: Otherwise, let's say if I don't promote them and I directly change my branch, switch branch to their other branch, right, Gabby's branch or this branch, if I go to this branch, you would see that these dashboards won't be able to shife, right, because a lot of these charts are being prepared by columns which are not promoted to the final shared model, right? 
 8:56: That's how useful it is. 
 8:56: So this is only for me if I, get this review from my CEO or my manager, I can quickly promote this. 
 9:02: Let's get back to my branch. 
 9:03: , so yeah, let's go to the workbook. 
 9:07: We go to the workbook la we can simply select this workbook option here, and we will quickly be moved to our workbook la. 
 9:11: So this is how our workbook layer look like on the right side of the pan, sorry, left side of the panel, we have all the data models or the tables of views I can say, which is currently my. 
 9:21: Topic is using what's a topic I will tell you about that. 
 9:24: So before that, as you can see, all these different tabs present below, every tab represents a single tile on our dashboard. 
 9:30: Let's say that sales, you would be, you would have seen this API tag on our dashboard. 
 9:33: Similarly, the top end products which I was discussing about it's awesome features. 
 9:36: It has been built here as you can see here, there are 10 number of products. 
 9:39: We are filtering up only topics. 
 9:40: So that was it was showing on our dashboard. 
 9:42: Similarly, the sky upload this, it's coming from this particular particular chart. 
 9:46: If we have to see the behind the scenes data of this actual value, we can select both. 
 9:49: From this tab so we can see both of these options, what are the columns which are being used, what are the values, and also we can see it from the results tab. 
 9:55: Yeah, that's another very useful and awesome feature. 
 9:58: OK, so these are all the different types of, I would say tabs from where we actually create these different and useful modules, and that's how they work. 
 10:06: So I was going to tell you about topics, right? 
 10:07: So let's move to the data modeling layer of what's say. 
 10:10: We have to a lot of analytics and filters related things, right? 
 10:12: So what's our topic? 
 10:13: Let us move to the modeling layer or layer for me. 
 10:17: Yeah, I'm here. 
 10:18: As you can see, you will be seeing words like topic here, revenue analytics, order analytics, orders, marketing, and that. 
 10:23: So what actually this means that so a topic you can consider that is a combination of views, selected views which a user wants to build for any particular use case or. 
 10:33: Particular business related item. 
 10:35: So let's say for example in our scheme or in our entire data model we have thousands of tables. 
 10:39: That is a really great feature and we are going to build a finance or analytics related or product analytics related dashboard. 
 10:43: So a product will be specific to only a particular thing, right? 
 10:47: So we only have to use out of those 1000, let's say they use only 5 or 6 of them, so. 
 10:52: And we have a separate finance team is going to work on those views, and I don't want them to, I don't want them to see all other of those tables, right? 
 10:58: And they can simply create a topic and that will be easier to navigate and set select, let's say different restrictions and access so that only they can go into those particular topic and can see those views which are needed, right? 
 11:08: For example, if I go to the marketing folder, it has only to use for events, topics, and users. 
 11:12: So then if I go to the orders fulfillment folder, we can see that there are only 2 uses for inventory items. 
 11:16: So folder we have an order and fulfillment related folder. 
 11:19: We have two topics inventory items or items. 
 11:21: So inventory items if I go. 
 11:23: Like here you can see the what's the modeling it all the different types of joints are defined here. 
 11:27: What is the base view on which we are building it, what is the growth of this particular topic, etc. 
 11:31: right? 
 11:31: So as you can see, we are only joining in total 5 or 6 tables, so views, and every time I see, so 56 views before this particular topic, and we are defining the joining relationship here, right? 
 11:41: So how do we actually do these joints? 
 11:43: That's also a very important, but a great feature only tackles it. 
 11:46: So we have a relationships file present in our model where all different types of relationships are defined. 
 11:50: Either writing the code or if you have to create a new table, you can also do that using a drag and draw functionality and those changes will automatically reflect here on your model. 
 11:58: I'll show that to you. 
 11:58: So all these different joints are defined like joining from e-commerce stage schema. 
 12:03: So, ecom is the schema and score defines the what's actually a differentiator between schema and the tables. 
 12:10: And similarly, this is the ecom view users we join them on left type of joint. 
 12:14: This is the column on which we joined. 
 12:16: We join it on user ID and the relation type is assumed to be. 
 12:19: I will tell you what this, what assumed actually means. 
 12:21: That's another really great and awesome feature. 
 12:23: So all these different types of models are defined, relationships are already defined in the relationships. 
 12:26: So whenever we create a new Topic we simply have to bring these different hierarchies or joints or refer those in our topic list so that we can get all those calls. 
 12:33: How do we do that? 
 12:33: That's how we do it. 
 12:34: We have a joints field and we can specify which particular table you are going to join with what. 
 12:38: For example, we have a hierarchy to find it. 
 12:40: Ecom order items is the base we have, which is going to be joined with the user on the facts or maybe any column which is already defined in the modeling these relationships so the ecom users is going to be joined on ecom order items. 
 12:49: Then inventory item item inventory items also going to be defined on. 
 12:52: items. 
 12:52: And after that, as you see, there is an indentation. 
 12:54: The definition of this indentation, it simply means that defines the hierarchy of how joints actually happens. 
 12:58: It means that ecom products cannot be directly joined with ecom order items, the base view. 
 13:01: It is going to be joined with the, what's the, our e-commentary items and then e-commentary items is going to be joined with other items. 
 13:06: So there's another hierarchy, as you see, after ecom products. 
 13:08: It means that econ distribution center is going to be first joined with ecom products. 
 13:11: Then after that we are going to join it with inventory items. 
 13:14: That's how the order hierarchy looks like and it gets defined. 
 13:16: Let's say if I have to, let's say. 
 13:19: Create a new joint in my other items topic. 
 13:21: This is the topic which we are using for creating all these different use cases, and, we have all these different types of views. 
 13:27: So how do I show it from the start? 
 13:29: It's only take these three particular joints in our revenue analytics topic and let me build these on top of it. 
 13:36: So I copy it here and I have to remove the space label label, OK, and remove these two things. 
 13:45: So right now, this is what I have to say. 
 13:50: Is there any so it means that our revenue analytics topic will have in total 3 different views joined together. 
 13:55: So what are those 3 views? 
 13:56: How I can look to those? 
 13:58: So let me go back to my own homepage folder,, so I can simply go to the tab and I can see what are the different types of topics or tools I have. 
 14:10: So as you see yours is the topics present here. 
 14:12: I can click here and order items. 
 14:15: These are inside the analytics folder and we in the order items we just created a few minutes ago. 
 14:19: Let me show you the order items label all items. 
 14:23: If I update this to revenue. 
 14:25: Because that sounds much what's it yeah. 
 14:31: So now we can go back to our edit topic in workbook and We can add another dog. 
 14:39: We can select the one which we want as you see analytics revenue. 
 14:42: This is the one which I we are going to build on and here is all the things that we need, right? 
 14:46: That's awesome. 
 14:47: And let's do some joints first, right? 
 14:49: That was the thing we are going to use. 
 14:50: So I want to add the sessions, so we only see. 
 14:55: What are the things inside this revenue inventory items, use a lot of apps and users. 
 14:58: I don't have any products and other details. 
 15:00: Let me join this products, so I can simply go to this builder. 
 15:05: I can select the view I want to join on. 
 15:07: I want to join on product, and then I have to select what field I have to use, so I will be using the product ID, so. 
 15:16: This ID is a tidy field and then left. 
 15:19: I don't know what type of relationship these two joints are, right? 
 15:21: I have maybe it can be 21, 121 or 2. 
 15:23: How do I get in for that. 
 15:24: That's where this awesome only feature comes in. 
 15:26: You can simply click in for a relationship, and it will tell me what type of relationship it is. 
 15:29: It's 1 to 1 awesome. 
 15:30: That means is that we don't, we won't have any duplicates. 
 15:32: We can simply add this. 
 15:34: And you will see the product is added in the statement, right? 
 15:38: So. 
 15:39: Let me quickly add my PC to charge. 
 15:42: Just a second. 
 15:44: So if I go back to my would say modeling lab, see how does this change look like, I can go back to model layer's works on my, here if I select my revenue analytics topic. 
 15:56: You would see the demo product is added joint. 
 15:58: What other things are in our items? 
 16:00: So we have ecom products. 
 16:01: We have demo product images, and we have e-com distribution centers. 
 16:04: Let's add these in our revenue analytics as well. 
 16:06: So we come back here again. 
 16:08: And he can join these things on inventory items. 
 16:13: You what I mean? 
 16:15: We can select the ecom scheme at this time previous time I select the wrong ones, and we can add. 
 16:21: The products from not many sessions. 
 16:24: We wanted the products right the product ID ID relationship is 1 to 1. 
 16:29: We can do it for better to have a double check for that. 
 16:32: Yeah, we had that. 
 16:34: So The product is added now. 
 16:37: Now we can quickly go to product. 
 16:38: We can join it. 
 16:39: I want the product images. 
 16:40: No, at first like the distribution centers. 
 16:42: I can go to. 
 16:44: Same you again. 
 16:45: I can add the distribution centers. 
 16:46: I can select the ID and from here, let me see on what it has been doing. 
 16:51: And you can go back to all embedded topics so that ecom products and e-com distribution centers that joined with e-com products, OK, with this ID we will do this ID and let's see the relationship and it's 21 also and we are the. 
 17:05: Great. 
 17:05: So as you see now, we'll be having distribution centers and that's how we simply do joints and only. 
 17:09: We can also directly write those or relationships inside this box as you see the distribution centers have come. 
 17:15: Let's say if I want to have the same topics here, I can simply copy paste this type of joint and add it here. 
 17:20: And if I save these changes. 
 17:23: Great, and I go back to my work. 
 17:24: I refresh it. 
 17:26: I am expected to see all the views just tightly. 
 17:29: Right, see product images, revenue sessions, top end products, all these things. 
 17:32: That's great. 
 17:33: So I have created this top end products as a separately, so let me remove this. 
 17:37: I will show you how. 
 17:38: That's a great feature actually. 
 17:40: Let's move to another awesome use case of only that's part of Excel. 
 17:45: So let's say I have a requirement and to get the net order value or average order value. 
 17:50: How do I actually build it? 
 17:51: I can simply add a new tab. 
 17:53: I can select the columns which I need. 
 17:54: So let's say I need the. 
 17:56: Created at one field and then after that I want the sales. 
 18:02: Net sales or sales. 
 18:07: It would be maybe. 
 18:09: Yeah, these are all the measures that I have created already. 
 18:11: I'll see you in a few minutes how I created those directly in the morning. 
 18:14: Now let me add the created that from here directly then. 
 18:18: Sorry, this is located at month. 
 18:20: I will remove this one. 
 18:22: And then we want the orders, so we have an orders count metric. 
 18:26: This is that awesome. 
 18:27: And let's say now I have to get the average order value, and I don't know the formula of it. 
 18:30: That's where another awesome AI feature of Uni comes in called GalaxyI because simply. 
 18:34: I can write here average order and and what you can just see the magic what it does. 
 18:39: It will automatically create a table for me which will have the average order value formula. 
 18:42: Yeah, you see how has it created that. 
 18:45: The Excel formula is B1 divided by C2, and if we see that it's actually correct. 
 18:48: The gross las some divided by the orders. 
 18:51: That's how easy it is, as you see just using Excel we can directly create these different types, and if you don't know the formula, you can also use the Cal CI feature. 
 18:57: Let's create only. 
 18:58: Now let's say simply I have to put a chart on top of this. 
 19:01: I can go to the chart layer and write in the chart layer game, an automatic chart gets created, but I have to use that KPI which I was having in my dashboard. 
 19:10: I can go to the KPI section. 
 19:11: And this KPI will show and then I can select what are the columns that I want here. 
 19:15: It's showing raw sales, but I want the, let's say average order value. 
 19:18: So I can quickly update this value to orders and we have the average order value. 
 19:22: And as you see what's this, this is nothing but just comparison if you have to compare those with let's say. 
 19:28: , what were the orders previous month or in total comparison, we can also do that. 
 19:32: So let me first to make this value, and I can add another field here. 
 19:36: I can select comparison and then inside this comparison. 
 19:39: What is the field on which I have to make this comparison? 
 19:41: I want to do this on a sales. 
 19:42: What was the saless last time. 
 19:44: And here, the second row, what is the percentage change we are? 
 19:47: You can say there is a 10% increase, and if I want to move this to orders, I can do that as well inside the orders and comparison there and the configure there. 
 19:55: The first and the second rows. 
 19:56: There was a total 8% increase in between all these two things. 
 19:59: There are other awesome features as well like image, progress, etc. 
 20:03: That's great and very useful. 
 20:05: So let's move on to the next thing. 
 20:07: I want to show you how we can use X lookups also directly that's another Excel feature which is very easy and very useful. 
 20:13: For example, if I had a condition where I would say we created this way, right? 
 20:19: We can see the results here. 
 20:21: Yeah, and we have these four fields, but I wanted to add the sessions count here, but I don't, I don't have a joint, so I can do an X lookup there. 
 20:28: How do I do that for doing an Exc lookup? 
 20:30: That's simple. 
 20:30: How we do it in Excel. 
 20:31: We should have another tab where we have those 5. 
 20:33: So you can see a sessions count already present here, right? 
 20:36: It is showing me the session start month and the sessions. 
 20:38: This can be my lookup field. 
 20:40: I can use this. 
 20:41: You will see coy lookup reference. 
 20:42: This is the lookup value I will need. 
 20:43: Let's go back to the query and let me quickly add a new field here. 
 20:48: To the right or left, where do I get me added to the left hand here. 
 20:51: I can do it's look up. 
 20:52: I can select the comparison field from this tab. 
 20:55: It will be this one. 
 20:56: On similar, then I can add the lookup field and the lookup value will be the follow B that is the account, right? 
 21:01: And boom, oh sorry, let me have the maxims boom, OK. 
 21:06: BIT that's not, it will be just me so you see the value has come for August is when if we check the position's call. 
 21:13: For August, it is a job. 
 21:16: August, OK, September 24th. 
 21:19: Let me check it for September 24. 
 21:22: 784 We don't have that. 
 21:26: I so that's all we can do it. 
 21:28: Then now we have this lookup value as present. 
 21:31: We can call it sessions down and you see without any showing create to that now if I have to add another type of conversion value on top of this, I can simply add another column here and that's called conversion rate. 
 21:42: I can write it on rate. 
 21:45: And I can do a simple Excel formula again that will be orders divided by sessions count. 
 21:50: If you don't want to write it, you can simply use the CalCI feature again, right? 
 21:53: That's great. 
 21:54: So you see the conversation rate has also come in. 
 21:56: Now you would remember the chart for conversation rate here. 
 21:59: I added some the rate. 
 22:01: That's also similarly we have used the XLloca feature. 
 22:04: If you go to the result, created one authors session, and upon this is coming from, see the lookup, yeah, that's awesome, right? 
 22:11: This is another great and awesome useful feature of Omni. 
 22:13: Then we have covered a lot of things. 
 22:14: What's left, yeah. 
 22:15: So let's see if I have to save that particular query which I created as a view, how do I do that? 
 22:20: So let me rename it first. 
 22:21: I can call it test query. 
 22:23: And I can. 
 22:27: Go to the doctor. 
 22:30: OK, so let me see. 
 22:33: Yeah, yeah, this is the one. 
 22:36: If I do the model, we can do or promote these changes to the shared model there, but I don't want to do that. 
 22:41: I can simply save this query as a topic. 
 22:43: So, save this query as a view. 
 22:45: This is the name and I can create it. 
 22:49: Wait, now you see, this is the query which will be created. 
 22:52: We can see the YAML code or the basic behind the C code for it. 
 22:55: We have all these dimensions present. 
 22:56: We have the measure account is a simple measure. 
 22:58: This is the raw only code which is being used. 
 23:00: The schema is the ecom schema, the query, all these things. 
 23:02: That's great, right? 
 23:04: That's how useful and simple it is. 
 23:06: And then let's move to another awesome feature which I told you, the top end products, right? 
 23:11: How do we create that? 
 23:12: So let's say, we have it somewhere. 
 23:16: Do you want me to use that directly or do I have to create it? 
 23:18: This is the top products. 
 23:20: It's also very simple. 
 23:22: And maybe be another dog would you. 
 23:25: And we can select the revenue analytics revenue topic and I want this month created a month and then I want the net sales. 
 23:37: Then after that what I want to do is I want to get the browns. 
 23:41: I can go to the product player. 
 23:43: I can select the brand, the category, both things what I want. 
 23:47: Did I get now I want to rank this on net sales. 
 23:51: That's very, very simple. 
 23:51: You just have to go to the toggle menu. 
 23:53: You can have these multiple already created features. 
 23:56: We can go to the aggregates. 
 23:57: You would see something called rank, yeah, rank. 
 24:00: That's how simple to create this on the basis of rank or the total sum. 
 24:06: So Can we do that again using a measure so that it's more accurate. 
 24:12: Yeah, it's showing it because we have removed the exes field itself exhas so this is the one. 
 24:17: This is this is an aggregate or measure I would say I'll use this. 
 24:23: For defining the ranks. 
 24:26: Yeah. 
 24:28: No, that's better. 
 24:29: You take it off, man. 
 24:31: And see the net sales maximum of 7370 for January 20842. 
 24:35: This is the Levi's brand. 
 24:36: This is the GA category. 
 24:37: If I just want to have it on the basis of brand, I can simply do that. 
 24:41: Great. 
 24:42: And now if I want to have a filter where I want to just select the top 10 brands, I can simply make this as a query view. 
 24:50: And I can I can add that as a filter. 
 24:51: Let me show you how I can do that. 
 24:53: Go to the filters. 
 24:54: There are multiple ways of doing it in me. 
 24:56: I can show you the simple one. 
 24:57: I can go to the filter. 
 24:58: I can select what type of I want. 
 25:00: It should be less than or equal to, let's say top 15 update. 
 25:04: Yeah, yeah, you would say just dot of 15 of 15. 
 25:07: You can order it by it. 
 25:11: That's how simple and useful it is. 
 25:14: No. 
 25:17: What are the things we can do? 
 25:18: We have covered all those things. 
 25:20: There's one very awesome and useful feature of which I wanted to cover that's called templated filtering or parameter space. 
 25:26: Before that, I can also show you how we can promote all these changes which I made directly to the branch. 
 25:32: So and make it available in my shared model. 
 25:34: You see, these are the different high value templated filters that test query I created, the relationships, the revenue topic, all these things I add to the branch. 
 25:41: I promote these changes. 
 25:42: I should fail if it fails, no worries, the test fails, and let's go to. 
 25:47: My modeling layer. 
 25:49: And the models. 
 25:51: This will go to the work. 
 25:52: Let's go to the main shared model there. 
 25:55: Develop And only, yeah, we are here in the model. 
 25:59: You see the analytics topic, you see all the different joints, right? 
 26:03: And after that, let's go to the ecom view. 
 26:05: Some we will see all these different changes. 
 26:11: You see the test query which is created. 
 26:13: You see the top end products query, all these things. 
 26:16: When we promoted, it's present in our shared modu directly. 
 26:18: Yeah, you can see that dimensions, dimensions are nothing but those column names or attributes and what the measures. 
 26:22: Measures are nothing, just different types of aggregations on top of the dimensions. 
 26:25: That's that as simple as that. 
 26:27: Like the bound, let me show you it in the order items here. 
 26:30: I have a lot of fields, so. 
 26:32: I was talking about the gross sales of the net sales term a lot of time. 
 26:34: How do we create that? 
 26:35: It's very simple, you see. 
 26:36: I have the net sales period. 
 26:37: What it does it. 
 26:38: It it subtracts my gross sales with the total returns of values I have canceled. 
 26:42: I get the net sales field or dimension, and then I am doing simple and aggregate a sum on top of it to get my net sales sum. 
 26:48: I'm defining the format of my currency. 
 26:49: It should be USD, similarly, the ros sales sum. 
 26:51: I make the sum. 
 26:52: Other things also you can see the return cancel sum, the created a related fields, total price, all those things. 
 26:59: You see that here we have an excess grants thing. 
 27:01: It means that this particular field called margin sum or the particular dimension or measure, it will be only visible to the finance team and let's say I'm not in the finance team, so I won't be able to see this field, but it means that I'm in the finance field. 
 27:11: That's why I'm able to see right? 
 27:12: so. 
 27:14: If we go to the other things, what else, yeah, I was going to talk to you about the templated filtering, right? 
 27:20: So let's go back to a dashboard again, documents. 
 27:24: Resin is the one which I'm using one right now. 
 27:29: You see the query test query average order value created all that also come. 
 27:33: We can also simply hide these as well. 
 27:34: We don't need a some we can hide this data as well, yeah. 
 27:38: You see a chart present here called High Value sales template what that actually means, yeah. 
 27:44: Let's say we have a use case, you would have heard about parameter-based filtering, right? 
 27:47: I, if I want to add, see just top 10 brands, I have to add that 10 as a parameter or hard coded value inside the dashboard, and it will just show me the top 10 brands. 
 27:55: If I have to select that this entire chart should be visible as a T or B, then I can do that by providing a parameter. 
 28:00: Parameter means that simply a user is going to provide those values and your dashboard is going to change or reflect those changes depending on the parameter that has been provided, right? 
 28:07: So here, for example, inside this template filtering, how it is different. 
 28:11: The user directly sends you or injects an SQL query instead of just a hard coded value. 
 28:16: What does this mean? 
 28:17: Let's say for example, we have a statement where We are doing a filter on the basis of age. 
 28:22: Now, I want to do that on the basis of location, so that will be very difficult, right? 
 28:27: How do I do that? 
 28:28: Then in that case, we have a feature only called depleted filter where the user can directly pass the equal statement. 
 28:32: Right, you don't have to write that sequel statement that will be written by your only developer, and you just have to select those words, right? 
 28:38: So you can, select age and your chart will be automated on the basis of age. 
 28:42: If you select, let's say another field what I told location, your chart will be automatically updated on the basis of location. 
 28:47: Yeah, that's how you can see the field picker works, right? 
 28:49: I think the behind the scenes will be same. 
 28:51: Like I have a category, the name, the brand. 
 28:53: Similarly, I can do that with help of filtering as well. 
 28:55: So that's what is another useful feature for me. 
 28:57: If I show you the code and how it works, I have created something. 
 29:01: Yeah, yeah, this is the view which is having the SQL query which I wrote to get this directly present. 
 29:07: So this is all the syntax look like. 
 29:08: , let me show you the Yarmail directly so that you will understand much better. 
 29:14: Templated filter, right, as you see, I have this particular high sale values. 
 29:18: I want to do it on the basis of sales price. 
 29:19: So this is a ginger type of sale syntax where redefine the query then the particular. 
 29:26: Field we have to use or the particular type of filter we are going to use this is for the main line amount select it as a filter and we select what type of column we are going to use for this filter. 
 29:32: That is sale price. 
 29:34: Solarly another thing can be I have to do a filter on the basis of status, right? 
 29:37: So high value sales include a cells as a filter and O or status is the column. 
 29:40: What is O Soo is nothing but the lias name for orders. 
 29:43: You see, sorry, order items, that's that's pure basic sequel. 
 29:47: Similar things as you see, where is this filter defined in line amount in status? 
 29:51: This is presented. 
 29:52: Midline amount we have selected type number. 
 29:54: The label similarly includes status. 
 29:56: We have selected type string, and we are suggesting a field called order item status as this particular value. 
 30:01: Similarly, I was talking about the parameters. 
 30:02: We can also pass parameters directly as here this is also a ginger-based template. 
 30:06: As you can see the difference between these two here, we're directly providing the value for day and weeks and early months. 
 30:11: Maybe it can be number 1234, whereas here in this templated filtering box, we are providing a sequel statement on an entire column. 
 30:17: If we see the raw sequQL query behind these things, these are nothing but case statements, and depending on the, what's the type of filter the user has selected, it automatically reflects that. 
 30:26: Let's see how this actually looks like in the dashboard. 
 30:27: Yeah, I didn't show you that. 
 30:28: That's it. 
 30:30: So. 
 30:31: These, these are the filters. 
 30:32: If I have to do it on the basis of what's the status, status is equal to processing completed, and I update my this particular chart will get updated on the basis of those two filters, you see. 
 30:44: And if I also want to change this particular filter and I have to do it on the basis of the midline value that is the net sales, let's select 100 something like that. 
 30:53: It will get updated on the basis of net sales so. 
 30:56: Oh, there is no less than 100, 0 sorry, equal to 100 value. 
 31:00: Let me do it later than sorry. 
 31:03: Yeah, oh, we have some bad news. 
 31:05: So that's how we can do it. 
 31:07: For this use case, I would say in the field get pick that switching that only has already created that we can use it. 
 31:11: That's much easy. 
 31:13: Right, yeah. 
 31:14: And what else I can show, I think we covered all the things which I had on my list and hope you like this entire Omni demo session. 
 31:21: I also enjoyed it. 
 31:22: Thanks. 
