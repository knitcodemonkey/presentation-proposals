# Styling React for Reuse

## Abstract:
We’ve all excitedly installed a third-party component that beautifully fit our functional needs, only to sacrifice design, and waste hours covering our code in !important tags to get it “close enough”.

I will use real-world examples to explore what makes a component easy to restyle, and how you can still use your preferred css approach to develop more widely-customizable components without causing all that pain.

## Details:
All code will be pre-written, and will run without an internet connection. After the talk, codepens and/or a git repo 
will be available for reference. 

* The good, the bad, and the ugly
    * Load a component, try to fit it into my page, and realize how painful it is. 
    * Try another component, one that works. One that doesn't hurt. 
    
* Compare good and bad examples of components using different css styles while discussing:
    * Functional versus lipstick styling
    * Inline, stylesheets, and css-in-js examples.
    * Reusable components are oftentimes not used for their original purpose
    
* Conclusion
    * I will show a page refreshing with multiple stylesheets, similar to http://www.csszengarden.com, to illustrate 
    how our newly stylized component can be re-skinned in wildly different ways, while keeping it's functionality intact.  

## Pitch:
The front-end programming sphere has exploded in recent years. Between state-based components, class naming conventions, and the inline versus stylesheet wars, it's difficult to wrap your head around your own components, let alone releasing them for reuse. 

My goal is to take all that information and distill it down into an easy to digest discussion for those who are looking to standardize their own components, or release their first components for public use. My goal is to help the community, at large, think about css in their OSS components in an extensible way.
