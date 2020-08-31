removeAllAttachmentsWhenArchived(notification)
{
  new Notification(notification).archivedCard().removeAllAttachments();
}
