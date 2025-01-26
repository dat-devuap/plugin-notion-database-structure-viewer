# **Notion Database Structure Viewer**
This plugin allows users to get database structure of a Notion database.

### 📝 **User Setting Notes:**
#### 🔧 **Set Up the Plugin Server:**
- A plugin server must be set up to use this feature. Follow the detailed guide to set up a plugin server on Render: [How to Deploy the Plugin Server on Render](https://docs.typingmind.com/plugins/plugins-server/how-to-deploy-plugins-server-on-render)

#### 🔑 **Set Up Your Notion API Key:**
- Go to the [Notion Integration Page](https://www.notion.so/profile/integrations) and create a new integration.
- Copy the key from the Integration Detail Page.
- Paste the key into the plugin's user settings:
  **Notion API Key:** `ntn_XXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXX`

For detailed instructions, visit the [Notion Integration API Documentation](https://developers.notion.com/docs/create-a-notion-integration)

#### 🔗 **Share Your Database with the Integration:**
- Open your database in Notion.
- Click the **“Share”** button in the top right.
- Select **“Invite”**, search for your integration name, and click **“Invite”** to grant access.

For detailed instructions, visit the [Notion API Connections Documentation](https://www.notion.com/help/add-and-manage-connections-with-the-api)

### 📌 **Important Notes:**

#### 👉 **Rate Limits:**
- There are rate limits for Notion API requests. Learn more at [Notion API Rate Limits](https://developers.notion.com/reference/request-limits#rate-limits).

### 💡 **Example Usage**  
> Could you provide the structure of the Employee Directory database from this Notion Database URL: https://www.notion.so/12345bcxyz?v=11111aaaaaa