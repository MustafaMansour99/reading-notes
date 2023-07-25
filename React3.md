# Metadata

***Metadata plays a significant role in enhancing the overall user experience and improving a website's search engine ranking. By including relevant metadata, developers can control how their web pages appear in search results and when shared on social media platforms. It ensures that the website is presented accurately and attractively to users and potential visitors.***


# Static Assets
**Next.js can serve static files, like images, under a folder called public in the root directory. Files inside public can then be referenced by your code starting from the base URL (/).**

**For example, if you add me.png inside public, the following code will access the image:**

# import Image from 'next/image'
 
export function Avatar() {
  return <Image src="/me.png" alt="me" width="64" height="64" />
}




## Configuring Metadata in Next.js
To configure metadata for your website, you can use the `next/head` component provided
by next.js which allows us to add meta tags and other relevant information that will be used by
search engines when indexing our site's content:
```jsx
import Head from 'next/head'
function MyApp({ Component, pageProps }) {
    return (
        <div>
        {/* Add head tag here */}
        </div>
        )
        }
        export default function App()
 