# Reading-Notes

                        ** Class-22 - Reading React Tesing and Deployment**



#### Describe a case where snapshot testing would be useful, and describe another case where it would be ineffective.

* A snapshot test is useful for a fully developed UI page that you want to ensure does not change throughout development. If you are consistently changing your UI, any saved snapshots will quickly become out of date, and will incorrectly cause your tests to fail.

#### What is the difference between full mount and shallow mount?

* Full mounting allows you render the  entire component as well as any children componens. Shallow mounting minimized the render of any imported components, and instead focused on fully rendering the curret component only.

#### What does npm run build do?

* It create a live website that refreshes as you write the code.
